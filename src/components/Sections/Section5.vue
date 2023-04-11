<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img class="background" src="../../assets/secao5/background.png" alt="" />

    <div class="conteudo">
      <div class="box1 card5">
        <img src="../../assets/secao5/celular1.png" alt="" />

        <div class="celular card1">
          <h2>Mural</h2>
          <p>
            Papéis espalhados pelo condomínio<br />
            ou email no spam?
          </p>
          <p class="bold">
            O Novo mural Livo permite <br />
            de forma organizada a comunicação<br />
            de tudo o que acontece<br />
            no condomínio.
          </p>
          <p class="card">Da campanha do agasalho à festa junina.</p>

          <Loguinho class="loguinho"></Loguinho>
        </div>
      </div>
      <div class="box1 card5 card4">
        <img src="../../assets/secao5/celular2.png" alt="" />

        <div class="celular card2">
          <h2>Notificações</h2>
          <p>
            Agora se for algo como limpeza da fachada<br />
            ou dedetização, o campo de notificações<br />
            serve muito bem para isso.
          </p>
          <Loguinho class="loguinho"></Loguinho>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import Loguinho from "../icons/Loguinho.vue";
</script>

<style scoped>
#section2 {
  background: none;
  margin: 0;
  padding: 0;
  margin-top: -0.7vw;
}
h1,
h2 {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

p {
  font-family: "ArticulatCF";
}

.background {
  margin: 0;
  padding: 0;
  width: 100%;
}

.conteudo {
  position: absolute;
  top: 0;
  width: 100%;
  height: 67.8%;
  z-index: 2;
  /* background: rgba(255, 0, 0, 0.105); */
  color: var(--color-gray);
  display: flex;
  flex-direction: column;
  align-items: center;
}

.box1 {
  margin-top: 4vw;
  display: flex;
  /* background: blue; */
  align-items: center;
}

.card5 {
  display: flex;
  align-items: center;
  top: 3vw;
  left: 1vw;
}
.card5 img {
  width: 23vw;
}

.celular {
  left: 7vw;
  top: -2vw;
}
.celular h2 {
  font-size: 5vw;
  font-weight: 600;
}

.celular p {
  width: 40vw;
  font-size: 2vw;
  font-weight: 400;
  line-height: 1.2em;
}

.bold {
  margin-top: 1.8vw;
  font-size: 2vw;
  font-weight: 700 !important;
  line-height: 1.2em;
}
.card1 {
  top: 1vw;
}

.card4 {
  margin-top: 8vw;
}
.card1 p {
  font-size: 2vw;
  margin-bottom: 40px;
}

.card1 .bold {
  margin-bottom: 0px;
}

.card1 .loguinho {
  top: 4vw;
  left: 28vw;
}
.loguinho {
  top: -7vw;
  width: 5vw;
}

.card2 .loguinho {
  top: 10vw;
}

.card {
  background: #9453d6;
  border-radius: 8px;
  margin-top: 2vw;
  font-weight: 400 !important;
  padding: 2px 10px;
}

@media screen and (max-width: 600px) {
  #section2 {
    margin-top: -1.9vw;
  }
}

@media screen and (max-width: 450px) {
  .card5 {
    display: flex;
    align-items: center;
    top: -3vw;
    left: 1vw;
  }
  .card4 {
    top: -5vw;
    margin-top: 0vw;
  }
}
@media screen and (max-width: 300px) {
  .card4 {
    top: -16vw;
    margin-top: 0vw;
  }
}
</style>
