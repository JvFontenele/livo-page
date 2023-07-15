<template>
  <carousel
    :items-to-show="4"
    class="carrocel"
    autoplay="1000"
    transition="2000"
    wrapAround
  >
    <slide key="1" >
      <img
        src="@/assets/carrocel/Rectangle.png"
        alt="Aplicativo para  gestão de  condomínio"
      />
    </slide>
    <slide key="2">
      <img
        src="@/assets/carrocel/Rectangle-1.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="3">
      <img
        src="@/assets/carrocel/Rectangle-2.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="4">
      <img
        src="@/assets/carrocel/Rectangle-3.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="5">
      <img
        src="@/assets/carrocel/Rectangle-4.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="6">
      <img
        src="@/assets/carrocel/Rectangle-5.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="7">
      <img
        src="@/assets/carrocel/Rectangle-6.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="8">
      <img
        src="@/assets/carrocel/Rectangle-7.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="9">
      <img
        src="@/assets/carrocel/Rectangle-8.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="10">
      <img
        src="@/assets/carrocel/Rectangle-9.png"
        alt="Aplicativo para  gestão de  condomínio"
      /> </slide
    ><slide key="11">
      <img
        src="@/assets/carrocel/Rectangle-10.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="12">
      <img
        src="@/assets/carrocel/Rectangle-11.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="13">
      <img
        src="@/assets/carrocel/Rectangle-12.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="14">
      <img
        src="@/assets/carrocel/Rectangle-13.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="15">
      <img
        src="@/assets/carrocel/Rectangle-14.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="16">
      <img
        src="@/assets/carrocel/Rectangle-15.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="17">
      <img
        src="@/assets/carrocel/Rectangle-16.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="18">
      <img
        src="@/assets/carrocel/Rectangle-17.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="19">
      <img
        src="@/assets/carrocel/Rectangle-18.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="20">
      <img
        src="@/assets/carrocel/Rectangle-19.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="21">
      <img
        src="@/assets/carrocel/Rectangle-20.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="22">
      <img
        src="@/assets/carrocel/Rectangle-21.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>
    <slide key="23">
      <img
        src="@/assets/carrocel/Rectangle-22.png"
        alt="Aplicativo para  gestão de  condomínio"
    /></slide>

    <template #addons> </template>
  </carousel>
</template>
<script setup>
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination, Navigation } from "vue3-carousel";

const images = [
  { id: 0, src: "src/assets/carrocel/Rectangle.png" },
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
