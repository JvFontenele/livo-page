<template>
  <footer class="footer">
    <div class="box">
      <div class="text">
        <h2>Transparência</h2>
        <p>POLÍTICA DE PRIVACIDADE</p>
        <p>POLÍTICA DE SEGURANÇA</p>
        <p>LGPD</p>
      </div>
      <div class="redes">
        <h2>Baixe nosso APP</h2>
        <img
          src="../assets/footer/Group-2.svg"
          alt="Condomínio conectado"
          @click="links.googlePlay"
        />
        <img src="../assets/footer/Group.svg" alt="" @click="links.appStore" />
      </div>
      <div class="qrcode">
        <p>SCANEIE PARA FALAR CONOSCO</p>
        <img src="../assets/footer/Group-4.svg" alt="Condomínio conectado" />
        <p>
          FEITO COM AMOR PARA TODOS <br />
          OS CONDOMÍNIOS
        </p>
        <h2>LIVO Comercial</h2>
        <img
          class="whats"
          src="../assets/footer/Group9.svg"
          alt="Condomínio conectado"
          @click="links.whats"
        />
      </div>
    </div>
    <div class="booton">
      <img src="../assets/footer/Group-3.svg" alt="Condomínio conectado" />

      <p>
        Al. Rio Negro, 1084 - Alphaville Industrial, Barueri - SP, 06453-051
        <br />
        contato@livoapp.com.br CNPJ 40.008.355/0001-41
      </p>
    </div>
  </footer>
</template>

<script setup>
import Logo from "./icons/Logo.vue";
import { links } from "../links";
</script>

<style scoped>
.footer {
  background: #1d1d1b;
  height: 25vw;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding: 2vw 60px;
  margin: 0;
  color: var(--color-gray);
}

h2 {
  font-size: 1.6vw;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
p {
  font-family: "ArticulatCF";
  font-size: 0.9vw;
  font-weight: 300;
}

.box {
  display: flex;
  width: 100%;
  justify-content: space-around;
}

.text p {
  margin-top: 10px;
}

.redes {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.redes img {
  width: 20vw;
  margin-top: 8px;
  cursor: pointer;
}

.qrcode {
  display: flex;
  flex-direction: column;
  align-items: start;
}
.qrcode img {
  width: 12vw;
  margin: 5px 0px;
}

.whats {
  width: 11vw !important;
  cursor: pointer;
}

.booton {
  top: -5vw;
  left: -10vw;
  display: flex;
}
.booton p {
  font-size: 1.4vw;
}
.booton img {
  margin-right: 10vw;
  width: 6vw;
}

@media screen and (max-width: 750px) {
  .footer {
    background: #1d1d1b;
    height: 30vw;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding: 2vw 60px;
    margin: 0;
    color: var(--color-gray);
  }
}

@media screen and (max-width: 300px) {
  .footer {

    height: 40vw;

    padding: 2vw 60px;


  }
}
</style>
