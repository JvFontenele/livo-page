<template>
  <footer class="footer">
    <div>
      <div>
        <h2>Transparência</h2>
        <p>POLÍTICA DE PRIVACIDADE</p>
        <p>POLÍTICA DE SEGURANÇA</p>
        <p>LGPD</p>
        <Logo class="logo"/>
      </div>
      <div></div>
      <div></div>
    </div>
  </footer>
</template>

<script setup>
import Logo from "./icons/Logo.vue";
</script>

<style scoped>
.footer {
  background: #1d1d1b;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 5px 90px;
  margin: 0;
}
</style>
