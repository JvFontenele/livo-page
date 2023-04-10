<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img class="background" src="../../assets/secao7/background.png" alt="" />

    <div class="conteudo">
      <div>
        <div class="cards">
          <img src="../../assets/secao7/Group-3.svg" alt="" />
          <h1>+15 ferramentas</h1>
          <p>
            Personalize as ferramentas do App <br />
            e regras de acordo com o que seu<br />
            condomínio necessita.<br />
          </p>
        </div>
        <div class="cards">
          <img src="../../assets/secao7/Group-5.svg" alt="" />
          <h1>Integração</h1>
          <p>
            Integramos com os principais <br />
            equipamentos do mercado.<br />
          </p>
        </div>
        <div class="cards">
          <img src="../../assets/secao7/" alt="" />
          <h1>Dashboard</h1>
          <p>
            Nosso painel de controle te mostra tudo<br />
            que você precisa, para o sindico e sua equipe<br />
            acompanhar seu condomínio<br />
          </p>
        </div>
      </div>

      <div class="img">
        <img class="" src="../../assets/secao7/Group-4.svg" alt="" />
      </div>
      <div>
        <div class="cards">
          <img src="../../assets/secao7/Group-3.svg" alt="" />
          <h1>+15 ferramentas</h1>
          <p>
            Personalize as ferramentas do App <br />
            e regras de acordo com o que seu<br />
            condomínio necessita.<br />
          </p>
        </div>
        <div class="cards">
          <img src="../../assets/secao7/Group-3.svg" alt="" />
          <h1>+15 ferramentas</h1>
          <p>
            Personalize as ferramentas do App <br />
            e regras de acordo com o que seu<br />
            condomínio necessita.<br />
          </p>
        </div>
        <div class="cards">
          <img src="../../assets/secao7/Group-3.svg" alt="" />
          <h1>+15 ferramentas</h1>
          <p>
            Personalize as ferramentas do App <br />
            e regras de acordo com o que seu<br />
            condomínio necessita.<br />
          </p>
        </div>
      </div>
    </div>
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
  top: 7vw;
  width: 100%;
  height: 67.8%;
  z-index: 2;
  display: flex;
  padding: 7.2vw;
  align-items: center;
}

.box {
  padding: 50vw;
}
.img {
  display: flex;
  align-items: center;
  justify-items: center;
}
.img img {
  width: 25vw;
  margin-right: 6vw;
}
.cards {
  width: 30vw;
  margin-bottom: 20px;
}
.cards img {
  width: 3vw;
}
.cards h1 {
  font-size: 2.1vw;
  color: var(--color-gray);
}
.cards p {
  font-size: 1.2vw;

  color: #575591;
}
</style>
