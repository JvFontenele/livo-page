<template>
  <header class="header">
    <Logo class="logo" />
    <div class="boxBtn">
      <ButtonsHeader
        title="LIVO COMERCIAL"
        icon="/src/assets/secao1/whatsIcon.svg"
      />
      <ButtonsHeader
        title="LIVO WEB"
        icon="/src/assets/secao1/headersetinhaIcon.svg"
      />
    </div>
  </header>
</template>

<script setup>
import ButtonsHeader from "./buttons/ButtonsHeader.vue";
import Logo from "./icons/Logo.vue";
</script>

<style scoped>
.header {
  height: 120px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5px 90px;
  margin: 0;
}

.logo {
  width: 100px;
}

.boxBtn {
  display: flex;
  width: 400px;
}
</style>
