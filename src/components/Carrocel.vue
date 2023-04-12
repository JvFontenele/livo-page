<template>
  <carousel
    :items-to-show="4"
    class="carrocel"
    autoplay="1000"
    transition="2000"
    wrapAround
  >
    <slide v-for="image in images" :key="image.id">
      <img :src="image.src" alt="Aplicativo para gestão de condomínio" />
    </slide>

    <template #addons> </template>
  </carousel>
</template>
<script setup>
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination, Navigation } from "vue3-carousel";

const images = [
  { id: 0, src: "src/assets/carrocel/Rectangle-0.png" },
  { id: 1, src: "src/assets/carrocel/Rectangle-1.png" },
  { id: 2, src: "src/assets/carrocel/Rectangle-2.png" },
  { id: 3, src: "src/assets/carrocel/Rectangle-3.png" },
  { id: 4, src: "src/assets/carrocel/Rectangle-4.png" },
  { id: 5, src: "src/assets/carrocel/Rectangle-5.png" },
  { id: 6, src: "src/assets/carrocel/Rectangle-6.png" },
  { id: 7, src: "src/assets/carrocel/Rectangle-7.png" },
  { id: 8, src: "src/assets/carrocel/Rectangle-8.png" },
  { id: 9, src: "src/assets/carrocel/Rectangle-9.png" },
  { id: 10, src: "src/assets/carrocel/Rectangle-10.png" },
  { id: 11, src: "src/assets/carrocel/Rectangle-11.png" },
  { id: 12, src: "src/assets/carrocel/Rectangle-12.png" },
  { id: 13, src: "src/assets/carrocel/Rectangle-13.png" },
  { id: 14, src: "src/assets/carrocel/Rectangle-14.png" },
  { id: 15, src: "src/assets/carrocel/Rectangle-15.png" },
  { id: 16, src: "src/assets/carrocel/Rectangle-16.png" },
  { id: 17, src: "src/assets/carrocel/Rectangle-17.png" },
  { id: 18, src: "src/assets/carrocel/Rectangle-18.png" },
  { id: 19, src: "src/assets/carrocel/Rectangle-19.png" },
  { id: 20, src: "src/assets/carrocel/Rectangle-20.png" },
  { id: 21, src: "src/assets/carrocel/Rectangle-21.png" },
  { id: 22, src: "src/assets/carrocel/Rectangle-22.png" },
];
</script>

<style scoped>
.carrocel {
  background: white;
  width: 100%;
  height: 25vw;
  max-height: 250px;
  top: -7px;
}
.carrocel img {
  width: 25vw;
  max-width: 250px;
}
@media screen and (max-width: 400px) {
  .carrocel {
    height: 20vw;
    max-height: 250px;
  }
  .carrocel img {
    width: 19vw;
    max-width: 250px;
  }
}
</style>
