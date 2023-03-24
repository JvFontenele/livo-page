<template>
  <section id="section1">
    <div class="box">
      <h1>
        Descubra <br />
        o novo aplicativo <br />
        do seu condomínio
      </h1>
      {{ windowWidth.innerWidth }}

      <p v-if="windowWidth > 400">
        Controle de acesso, encomendas, reservas, <br />
        comunicados entre diversas soluções para te levar <br />
        do ZERO – 100 % Tecnológico.
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
    padding: 0em 9em 5em 10vw;
  }
  h1 {
    font-size: 6vw;
    line-height: 0.9em;
    margin: 0 0 10px 0;
  }
  p {
    margin: 0;
    padding: 0;
    font-family: "ArticulatCF";
    font-size: 2.2vw;
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
    padding: 3vw 0em 0em 10vw;
  }
  h1 {
    font-size: 9vw;
    line-height: 0.8em;
    margin: 0 0 10px 0;
  }
  p {
    margin: 0;
    padding: 0;
    font-family: "ArticulatCF";
    font-size: 4vw;
    max-width: 280px;
  }
}
</style>
