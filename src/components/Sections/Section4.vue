<template>
  <section id="section2" class="background">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <!-- <img  src="../../assets/secao4/background.svg" alt="" /> -->

    <div class="conteudo">
      <div class="box1 card1">
        <img src="../../assets/secao4/lista.svg" alt="Controle de acesso" />
        <div class="box1-texto">
          <h2>Eventos e festas</h2>
          <p>
            Sem mais aquela lista no papel.<br />
            Controle separado para festas<br />
            e grandes eventos<br />
          </p>
        </div>
      </div>
      <div class="box1 card2">
        <div class="box1-texto">
          <h2>
            Prestadores de serviço <br />
            ou recorrentes
          </h2>
          <p>
            Facilmente cadastre, acompanhe<br />
            histórico ou faça bloqueio<br />
            instantâneo no app<br />
          </p>
        </div>
        <img
          src="../../assets/secao4/foto.svg"
          alt="Gestão de encomendas em condomínio através de aplicativo"
        />
      </div>
      <div class="box1 card3">
        <img
          src="../../assets/secao4/celulares.svg"
          alt="Gestão de correspondência em condomínio através de aplicativo"
        />
        <div class="box1-texto">
          <h2>Check in e check out</h2>
          <p>
            Programe a entrada de uma visita<br />
            e o último dia dela no local.
          </p>
        </div>
      </div>
      <div class="box1 card4">
        <div class="box1-texto">
          <h2>
            Controle <br />
            de encomendas
          </h2>
          <p>
            Simples para quem opera no dia a dia <br />
            a tarefa de registrar, comunicar<br />
            e garantir a entrega para o proprietário.<br />
          </p>
        </div>
        <img
          src="../../assets/secao4/cara.svg"
          alt="Aplicativo para gestão de condomínio e comunicação entre moradores"
        />
      </div>

      <div class="box1 card5">
        <img
          src="../../assets/secao4/celular.png"
          alt="Controle de encomendas em condomínio através de aplicativo"
        />

        <div class="celular">
          <Loguinho class="loguinho"></Loguinho>
          <h2>Ocorrências</h2>
          <p>
            Usuário livo se deparou com algo estranho, <br />
            danificado ou quer sinalizar de forma<br />
            organizada para o síndico?
          </p>
          <p class="bold">
            Ocorrências é a ferramenta <br />
            que faz acontecer.
          </p>
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
  margin: 0;
  padding: 0;
  margin-top: -0.8vw;
}

.background {
  background: url(../../assets/secao4/background.svg);
  background-position: center; 
  background-repeat: no-repeat;
  background-size: cover;
  margin: 0;
  padding: 0;
  height: 150vw;
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
.box1 img {
  width: 22vw;
}
.box1-texto {
  display: flex;
  flex-direction: column;
  padding: 1vw;
  width: 500px;
  width: 35vw;
}

.box1-texto h2 {
  font-size: 2.8vw;
  line-height: 1em;
  font-weight: 500;
  margin-bottom: 1vw;
}
.box1-texto p {
  font-size: 2vw;
  line-height: 1.2em;
  font-weight: 100;
}
.card1 .box1-texto {
  /* background: maroon; */
  margin: 0px 4vw;
}

.card2 {
  left: 10vw;
}

.card3 img {
  right: 6vw;
  width: 25vw;
}

.card4 {
  top: -2vw;
  align-items: end;
}
.card4 .box1-texto {
  width: 42vw;
}
.card4 img {
  width: 32vw;
}
.card4 h2 {
  font-size: 5vw;
}

.card5 {
  display: flex;
  align-items: center;
  top: 2vw;
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
  font-size: 2vw;
  font-weight: 400;
  line-height: 1.2em;
}

.bold {
  /* background: red; */
  margin-top: 20px;
  font-size: 2vw;
  font-weight: 700 !important;
  line-height: 1.2em;
}

.loguinho {
  top: -7vw;
  width: 5vw;
}

@media screen and (max-width: 600px) {
  #section2 {
    margin-top: -2vw;
  }
}

@media screen and (max-width: 400px) {
}
</style>
