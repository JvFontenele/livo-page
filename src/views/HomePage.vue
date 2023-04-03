<template>
  <main>
    <Header />
    <Section1 class="section1" />
    <Section2 class="section2" />
    <Section3 class="section2" />
    <Section4 class="section2" />
    <Footer class="footer" />
  </main>
</template>

<script setup>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import Section1 from "../components/Sections/Section1.vue";
import Section2 from "../components/Sections/Section2.vue";
import Section3 from "../components/Sections/Section3.vue";
import Section4 from "../components/Sections/Section4.vue";
</script>

<style scoped>
.section1 {
  position: absolute;
}
.footer {
  margin-top: -8px;
}
@media screen and (max-width: 400px) {
  .section1 {
    position: absolute;
  }
}
</style>
