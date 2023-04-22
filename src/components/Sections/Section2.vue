<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img
      class="background"
      src="../../assets/secao2/background-foquete.svg"
      alt="Aplicativo para condomínio"
    />

    <div class="conteudo">
      <div class="boxConteudo">
        <h1><LogoSNome class="logo" /><span>#LIVO</span>space</h1>
        <div class="box-descricao">
          <h2>
            Nossa maior missão é diminuir burocracias, lentidão e falta de
            comunicação.
          </h2>
          <p>Chegou o seu momento de entrar em uma nova Era.</p>
          <div class="btn-conteudo">
            <span>#LIVOspace</span> Conecte seu condomínio.
          </div>
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
  width: 47vw;
  border-radius: 80px;
  font-size: 2.3vw;
  font-weight: 300;
}

.btn-conteudo span {
  margin-left: 20px;
  margin-right: 5px;
  font-weight: 600;
}

@media screen and (max-width: 600px) {
  #section2 {
    background: none;
    margin: 0;
    padding: 800px;
    padding: 0;
  }
  .conteudo {
    position: absolute;
    top: 25vw;
    width: 100%;
    height: 70.8%;
    z-index: 2;
  }

  .btn-conteudo span {
    margin-left: 10px;
    margin-right: 4px;
    font-weight: 400;
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

  .btn-conteudo span {
    margin-left: 10px;
    margin-right: 4px;
    font-weight: 600;
  }
}

@media screen and (max-width: 400px) {
  #section2 {
    background: none;
    margin: 0;
    padding: 800px;
    padding: 0;
  }

  .conteudo {
    position: absolute;
    top: 35vw;
    width: 100%;
    height: 50.8%;
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

  .btn-conteudo span {
    margin-left: 10px;
    margin-right: 4px;
    font-weight: 600;
  }
}
</style>
