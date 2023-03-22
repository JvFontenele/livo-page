<template>
  <main>
    <Header />
    <Section1 class="section1" />
    <Section2 class="section2" />
    <Footer />
  </main>
</template>

<script setup>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import Section1 from "../components/Sections/Section1.vue";
import Section2 from "../components/Sections/Section2.vue";
</script>

<style scoped>
.section1 {
  position: absolute;
}
@media screen and (max-width: 400px) {
  .section1 {
    position: absolute;
  }
  .section2 {
  }
}
</style>
