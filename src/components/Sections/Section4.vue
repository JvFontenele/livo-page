<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img class="background" src="../../assets/secao4/Group 2.png" alt="" />

    <div class="conteudo"></div>
  </section>
</template>

<script setup>
import LogoSNome from "../icons/LogoSNome.vue";
</script>

<style scoped>
#section2 {
  background: none;
  margin: 0;
  padding: 0;
  margin-top: -8px;
}

.background {
  margin: 0;
  padding: 0;
  width: 100%;
}

.conteudo {
  position: absolute;
  top: 30vw;
  width: 100%;
  height: 67.8%;
  z-index: 2;
}

.boxConteudo {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  color: var(--color-gray);
}

h1 {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 6vw;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 25vw;
}

.logo {
  width: 6vw;
  display: block;
  margin-right: 10px;
}

h1 span::before {
  content: " ";
  display: inline-block;
  font-weight: bolder;
  height: 5vw;
  top: 0.8vw;
  margin: 0px 3vw;
  width: 3px;
  background: var(--color-gray);
}

.box-descricao {
  padding: 0 20vw;
}

h2 {
  font-size: 4vw;
  line-height: 1.2em;
}
p {
  margin: 25px 0;
  font-size: 2vw;
  font-weight: 200;
  padding: 0;
}

.btn-conteudo {
  background: var(--color-gray);
  color: var(--color-margenta-light);
  display: flex;
  align-items: center;
  height: 4vw;
  width: 45vw;
  border-radius: 80px;
  font-size: 2.5vw;
}

.btn-conteudo span {
  margin-left: 25px;
  margin-right: 5px;
  font-weight: 600;
}

@media screen and (max-width: 600px) {
}

@media screen and (max-width: 400px) {
  #section2 {
    background: none;
    margin: 0;
    padding: 800px;
    padding: 0;
  }
  .background {
    margin: 0;
    padding: 0;
    width: 100%;
    margin-top: 120px;
    position: relative;
  }
  .conteudo {
    position: absolute;
    top: 57vw;
    width: 100%;
    height: 67.8%;
    z-index: 2;
  }
  .box-descricao {
    padding: 0 15vw;
  }

  h1 span::before {
    width: 1px;
  }
  h1 {
    margin-top: 15px;
    height: 23vw;
  }

  h2 {
    font-size: 5vw;
    line-height: 1.2em;
  }
  p {
    margin: 10px 0;
    font-size: 2vw;
    font-weight: 200;
    padding: 0;
  }
}
</style>
