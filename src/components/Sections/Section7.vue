<template>
  <section id="section2" class="background">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <!--  <img
      class="background"
      src="../../assets/secao7/background.png"
      alt="Gestão de correspondência"
    /> -->

    <div class="conteudo">
      <div>
        <div class="cards">
          <img
            src="../../assets/secao7/Group-3.svg"
            alt="Condomínio conectado"
          />
          <h1>+15 ferramentas</h1>
          <p>
            Personalize as ferramentas do App e regras de acordo com o que seu
            condomínio necessita.<br />
          </p>
        </div>
        <div class="cards">
          <img
            src="../../assets/secao7/Group-5.svg"
            alt="Controle de acesso "
          />
          <h1>Integração</h1>
          <p>
            Integramos com os principais <br />
            equipamentos do mercado.<br />
          </p>
        </div>
        <div class="cards">
          <img
            src="../../assets/secao7/Group-5.svg"
            alt="Gestão de condominio"
          />
          <h1>Dashboard</h1>
          <p>
            Nosso painel de controle te mostra tudo que você precisa, para o
            sindico e sua equipe acompanhar seu condomínio<br />
          </p>
        </div>
      </div>

      <div class="img">
        <img
          class=""
          src="../../assets/secao7/Group-4.svg"
          alt="App para moradores"
        />
      </div>
      <div>
        <div class="cards">
          <img
            src="../../assets/secao7/Group-1.svg"
            alt="Aplicativo para gestão de condomínio e comunicação entre moradores"
          />
          <h1>Meio ambiente</h1>
          <p>
            Reduzimos carbono diminuindo<br />
            as filas de carros e papelada.
          </p>
        </div>
        <div class="cards">
          <img
            src="../../assets/secao7/Group-2.svg"
            alt="Gestão de correspondência em condomínio através de aplicativo"
          />
          <h1>Plug and play</h1>
          <p>
            Nosso time te ajuda na parte <br />
            de cadastro e implantação
          </p>
        </div>
        <div class="cards">
          <img src="../../assets/secao7/Group.svg" alt="Livo LGPD" />
          <h1>LGPD</h1>
          <p>
            Seguimos o padrão LGPD (dados <br />
            criptografados, protegidos e com<br />
            apenas a finalidade para acesso<br />
            ao app)
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
  margin: 0;
  padding: 0;
  margin-top: -0.88vw;
}

.background {
  background: #a3afde;
  margin: 0;
  padding: 0;
  height: 50vw;
  width: 100%;
}

.conteudo {
  position: absolute;
  top: 7vw;
  width: 100%;
  height: 68.8%;
  z-index: 2;
  display: flex;
  padding: 11vw;
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
  width: 28vw;
  margin-bottom: 2vw;
}
.cards img {
  width: 2.5vw;
}
.cards h1 {
  font-size: 2.1vw;
  color: var(--color-gray);
}
.cards p {
  font-size: 1.4vw;
  color: #575591;
}

@media screen and (max-width: 600px) {
  #section2 {
    margin-top: -3vw;
  }

  @media screen and (max-width: 600px) {
    .background {
  background: #a3afde;
  margin: 0;
  padding: 0;
  height: 70vw;
  width: 100%;
}
    .cards p {
      font-size: 1.7vw;
      color: #575591;
    }
    .background {
      margin: 0;
      padding: 0;
      width: 140%;
    }
  }

  .img {
    display: flex;
    align-items: center;
    justify-items: center;
  }
  .img img {
    width: 25vw;
    margin-right: 5vw;
  }
  .cards {
    width: 28vw;
    margin-bottom: 0vw;
  }
  .cards img {
    width: 2.5vw;
  }
  .cards h1 {
    margin-top: -6px;
    font-size: 3vw;
    color: var(--color-gray);
  }
  .cards p {
    font-size: 2vw;

    color: #575591;
  }
}

@media screen and (max-width: 400px) {
  #section2 {
    margin-top: -3vw;
  }
  .background {
    margin: 0;
    padding: 0;
    width: 150%;
  }
  .conteudo {
    top: 5vw;
  }

  .img {
    display: flex;
    align-items: center;
    justify-items: center;
  }
  .img img {
    width: 25vw;
    margin-right: 5vw;
  }
  .cards {
    width: 28vw;
    margin-bottom: 0.5vw;
  }
  .cards img {
    width: 2.5vw;
  }
  .cards h1 {
    margin-top: -7px;
    font-size: 2.8vw;
    color: var(--color-gray);
  }
  .cards p {
    font-size: 1.8vw;
    color: #575591;
  }
}
</style>
