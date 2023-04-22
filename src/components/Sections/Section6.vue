<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img
      class="background"
      src="../../assets/secao6/background.png"
      alt="Condomínio conectado"
    />

    <div class="conteudo">
      <div class="box">
        <p class="nuvemTexto">
          Acesso remoto <br />
          sem necessidade<br />
          de máquinas locais. <br />
        </p>
        <div class="nuvem">
          <h1>Cloud</h1>
          <img
            src="../../assets/secao6/nuvem.svg"
            alt="Aplicativo para gestão de condomínio"
          />
        </div>
        <div class="texto">
          <h2>Otimização de custos</h2>
          <p>
            + velocidade e segurança<br />
            para seu condomínio
          </p>
        </div>
      </div>
      <img
        class="boxImagem"
        src="../../assets/secao6/boneco.svg"
        alt="Controle de encomendas"
      />
    </div>
  </section>
</template>

<script setup></script>

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
  top: 0vw;
  width: 100%;
  height: 97%;
  z-index: 2;
  display: flex;
  justify-content: center;
  align-items: center;
  color: var(--color-gray);
}

.box {
  top: -20px;
}

.boxImagem {
  width: 32vw;
  top: 1vw;
  padding: 0;
  margin: 0;
}
.nuvem {
  padding: 0;
  margin: 0;
  display: flex;
}
.nuvem img {
  width: 22vw;
}

.nuvem h1 {
  font-size: 5vw;
  font-weight: 600;
  margin-right: 1.5vw;
}

.nuvemTexto {
  position: absolute;
  top: 0.7vw;
  left: 17vw;
  z-index: 2;
  font-weight: 200;
  font-size: 1.5vw;
  line-height: 1.3em;
}

.texto h2 {
  font-size: 2.5vw;
  font-weight: 600;
}
.texto p {
  font-size: 1.4vw;
  font-weight: 200;
}

@media screen and (max-width: 600px) {
  .texto p {
    font-size: 2vw;
    font-weight: 200;
  }
  .texto h2 {
    font-size: 3vw;
    font-weight: 600;
  }

  .nuvemTexto {
    position: absolute;
    top: 0.7vw;
    left: 18vw;
    z-index: 2;
    font-weight: 200;
    font-size: 1.8vw;
    line-height: 1.3em;
  }
}

@media screen and (max-width: 400px) {
}
</style>
