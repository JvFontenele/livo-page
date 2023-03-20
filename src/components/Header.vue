<template>
  <header class="header">
    <Logo class="logo" />
    <div>
      <ButtonsHeader title="LIVO COMERCIAL" />
    </div>
  </header>
</template>

<script setup>
import ButtonsHeaderVue from "./buttons/ButtonsHeader.vue";
import Logo from "./icons/Logo.vue";
</script>

<style scoped>
.header {
  background: var(--vt-c-white);
  height: 90px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5px 90px;
  margin: 0;
}

.logo {
  width: 60px;
}
</style>
