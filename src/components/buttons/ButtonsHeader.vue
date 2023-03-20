<template>
  <button>{{ title }}</button>
</template>

<script setup>
import { toRefs, toRef } from "vue";

const title = toRef(props, "title");
</script>

<style></style>
