<template>
  <footer class="footer">
    <div class="box">
      <div class="text">
        <h2>Transparência</h2>
        <p>POLÍTICA DE PRIVACIDADE</p>
        <p>POLÍTICA DE SEGURANÇA</p>

        <p>
          <a
            href="https://www.livoapp.com.br/lgpd.php"
            style="color: #fff; text-decoration: none"
            target="_blank"
            >LGPD</a
          >
        </p>
        <div class="icones-redes">
          <img
            @click="links.instagram"
            src="../assets/footer/instagram.svg"
            alt="Instagram"
          />
          <img
            @click="links.youtobe"
            src="../assets/footer/youtobe.svg"
            alt="Instagram"
          />
        </div>
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
        <p>ESCANEIE PARA FALAR CONOSCO</p>
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
          @click="links.whatsSuport"
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
// import Logo from "./icons/Logo.vue";
import { links } from "../links";
</script>

<style scoped>
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

.icones-redes {
  margin-top: 1vw;
  display: flex;
}

.icones-redes img {
  cursor: pointer;
  width: 3.5vw;
  margin-left: 10px;
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
    padding: 2vw 10px;
    height: 40vw;
  }
  .booton {
    top: -5vw;
    left: -20vw;
    display: flex;
  }
  .whats {
    width: 19vw !important;
    cursor: pointer;
  }
  .text p {
    font-size: 6px;
  }
  .qrcode P {
    font-size: 6px;
  }
}

@media screen and (max-width: 300px) {
  .footer {

    padding: 2vw 10px;
  }
  h2 {
  font-size: 1.6vw;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
  p {
  font-family: "ArticulatCF";
  font-size: 1.2vw !important;
  font-weight: 300;
}
}
</style>
