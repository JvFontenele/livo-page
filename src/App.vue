<template>
  <Loading @load="carregar()" v-if="loading"></Loading>
  <RouterView />
  <Whats />
</template>

<script setup>
import Whats from "./components/Whats.vue";
import Loading from "./components/loading.vue";
import { ref, onBeforeMount } from "vue";
const loading = ref(true);
function carregar() {
  setInterval(() => {
    loading.value = false;
  }, 8500);
}
onBeforeMount(() => {});
</script>

<style>
h1,
h2 {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

p {
  font-family: "ArticulatCF";
}
</style>
