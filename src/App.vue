<template>
  <Loading ></Loading>
  <RouterView />
  <Whats />
</template>

<script setup>
import Whats from "./components/Whats.vue";
import Loading from "./components/loading.vue";

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
