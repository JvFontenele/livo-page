<template>
  <section id="section1">
    <div class="box">
      <h1>
        Descubra <br />
        o novo aplicativo <br />
        do seu condomínio
      </h1>
      {{ windowWidth.innerWidth }}

      <p v-if="windowWidth > 300">
        Controle de acesso, encomendas, reservas, comunicados <br />
        entre diversas soluções para te levar do <br />
        ZERO – 100 % Tecnológico.
      </p>
    </div>
  </section>
</template>

<script setup>
const windowWidth = window.innerWidth;
</script>

<style scoped>
#section1 {
  margin: 0;
  padding: 0;
  display: block;
  width: 100%;
}

.box {
  display: block;
  padding: 0em 9em 7em 15vw;
}

h1 {
  padding: 0;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: 600;
  font-size: 6.2vw;
  line-height: 0.8em;
  margin: 0 0 35px 0;
  color: var(--color-margenta);
}
p {
  margin: 0;
  padding: 0;
  font-family: "ArticulatCF";
  font-size: 1.7vw;
  line-height: 1em;
}

@media screen and (max-width: 600px) {
  .box {
    display: block;
    padding: 0em 8em 5em 10vw;
  }
  h1 {
    font-size: 5.5vw;
    line-height: 0.9em;
    margin: 0 0 10px 0;
  }
  p {
    margin: 0;
    padding: 0;
    font-family: "ArticulatCF";
    font-size: 3vw;
  }
}

@media screen and (max-width: 400px) {
  #section1 {
    margin: 0;
    padding: 0;
    display: block;
    width: 100%;
    height: 500px;
  }
  .box {
    display: block;
    padding: 3vw 1em 0em 3vw;
  }
  h1 {
    font-size: 6vw;
    line-height: 0.8em;
    margin: 0 0 10px 0;
  }
  p {
    margin: 0;
    padding: 0;
    font-family: "ArticulatCF";
    font-size: 2.7vw;
    max-width: 260px;
  }
}
</style>
