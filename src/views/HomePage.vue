<template>
  <main>
    <Header />
    <Section1 class="section1" />
    <Section2 class="section2" />
    <Carrocel />
    <Section3 class="section2" />
    <Section4 class="section2" />
    <Section5 class="section2" />
    <Section6 class="section2" />
    <Section7 class="section2" />

    <Marcas />
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
import Section5 from "../components/Sections/Section5.vue";
import Section6 from "../components/Sections/Section6.vue";
import Section7 from "../components/Sections/Section7.vue";
import Marcas from "../components/Marcas.vue";
import Carrocel from "../components/Carrocel.vue";
import Whats from "../components/Whats.vue";
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
