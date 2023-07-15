<template>
  <header class="header">
    <Logo class="logo" />
    <div class="boxBtn">
      <!-- <ButtonsHeader
        @click="links.whats"
        title="LIVO COMERCIAL"
        icon="/src/assets/secao1/whatsIcon.svg"
      />
      <ButtonsHeader
        @click="links.web"
        title="LIVO WEB"
        icon="/src/assets/secao1/headersetinhaIcon.svg"
      /> -->

      <button class="btn"  @click="links.whats">
        LIVO COMERCIAL
      <img class="img" src="@/assets/secao1/whatsIcon.svg" />
    </button>
    <button class="btn"  @click="links.web">
      LIVO WEB
      <img class="img" src="@/assets/secao1/headersetinhaIcon.svg" />
    </button>
    </div>
  </header>
</template>

<script setup>
import ButtonsHeader from "./buttons/ButtonsHeader.vue";
import Logo from "./icons/Logo.vue";
import { links } from "../links";
</script>

<style scoped>
.header {
  width: 100%;
  height: 120px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5px 90px;
  margin: 0;
}

.logo {
  min-width: 90px;
  max-width: 95px;
}

.boxBtn {
  display: flex;
  width: 400px;
}

@media screen and (max-width: 600px) {
  .header {
    height: 120px;
    justify-content: space-evenly;
    padding: 0;
  }

  .logo {
    min-width: 60px;
    max-width: 70px;
  }

  .boxBtn {
    display: flex;
    width: 250px;
  }
}

@media screen and (max-width: 400px) {
  .header {
    height: 70px;
    justify-content: none;
    padding: 0;
    margin: 0;
  }

  .logo {
    min-width: 50px;
    max-width: 60px;
    /* margin-right: 15px; */
  }

  .boxBtn {
    display: flex;
    max-width: 250px;
  }
}





.btn {
  background: var(--color-btn-header);
  color: var(--color-gray);
  min-width: 172px;
  display: flex;
  height: 42px;
  align-items: center;
  justify-content: center;
  margin: 0;
  border: none;
  border-radius: 60px;
  cursor: pointer;
  margin-left: 10px;
  padding: 15px 10px;
  font-weight: 600;
}

.btn:hover {
  background: var(--color-btn-header-hover);
}
.img {
  width: 20px;
  margin-bottom: 2px;
  margin-left: 10px;
}

@media screen and (max-width: 600px) {
  .btn {
    min-width: 130px;
    font-size: 0.6em;
    padding: 0px 0px;
  }
}

@media screen and (max-width: 400px) {
  .btn {
    min-width: 110px;
    height: 32px;
    font-size: 0.6em;
    padding: 0px 0px;
  }
  .img {
    width: 15px;
    margin-bottom: 2px;
    margin-left: 5px;
  }
}
</style>
