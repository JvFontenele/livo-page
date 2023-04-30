<script setup></script>
<template>
  <div class="fundo">
    <div class="textos">
      <div class="texto1">
        <h1>LIVO</h1>
        <h2>
          Seu condomínio <br />
          conectado
        </h2>
      </div>
      <div class="texto2">
        <h2>#LIVOspace</h2>
      </div>
    </div>
    <img
      @load="$emit('load')"
      class="logo"
      src="../assets/loading/livo-logo.png"
      alt=""
    />
  </div>
</template>

<style scoped>
.fundo {
  position: fixed;
  top: 0;
  left: 0;
  background: #f8f6f7;
  display: flex;
  flex-direction: column;
  align-items: center;
  /* justify-content: center; */
  z-index: 9999;
  height: 100vh;
  width: 100%;
  z-index: 5000;
}

.logo {
  height: 35vw;
}

.textos {
  display: flex;
  width: 100%;
  padding: 1.5vw;
  color: var(--color-btn-header);
  justify-content: space-between;
}

.texto1 {
  display: flex;
}

h1 {
  margin: 0;
  font-weight: 600;
  font-size: 3vw;
}
h1::after {
  content: " ";
  display: inline-block;
  font-weight: bolder;
  height: 2.5vw;
  top: 0.4vw;
  margin: 0px 1vw;
  width: 2px;
  background: var(--color-btn-header);
}

h2 {
  font-weight: 400;
  padding: 1.1vw 0;
  line-height: 0.9em;
  font-size: 1.7vw;
}
</style>
