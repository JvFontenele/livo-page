<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img
      class="background"
      src="../../assets/secao2/background-foquete.svg"
      alt=""
    />

    <div class="conteudo">
      <div class="boxConteudo">
        <h1>#LIVOspace</h1>
        <div class="box-descricao">
          <h2>
            Nossa maior missão é diminuir <br />
            burocracias, lentidão e falta de <br />
            comunicação. <br />
          </h2>
          <p>Chegou o seu momento de entrar em uma nova Era.</p>
          <div class="btn-conteudo">
            <span>#LIVOspace</span> Conecte seu condomínio
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
#section2 {
  background: none;
  margin: 0;
  padding: 0;
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
  border: 5px solid red;
}

.boxConteudo {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  color: var(--color-gray);
}

h1 {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 5vw;
  font-weight: 600;
  text-align: center;
}

.box-descricao {
  padding: 0 20vw;
}

h2 {
  font-size: 4vw;
  line-height: 1.2em;
}
p {
  margin: 10px 0;
  font-size: 2vw;
  font-weight: 200;
  padding: 0;
}

.btn-conteudo {
  background: var(--color-gray);
  color: var(--color-margenta);
  padding: 5px;
  border-radius: 80px;
  font-size: 2vw;
  line-height: 1.2em;
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
    margin-top: 15px;
    position: relative;
  }
}
</style>
