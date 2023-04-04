<template>
  <section id="section2">
    <!-- <img class="foquete" src="../../assets/secao2/foquete.svg" alt="" /> -->
    <img class="background" src="../../assets/secao3/background.svg" alt="" />

    <div class="conteudo">
      <div class="boxConteudo">
        <h1>Ferramentas LIVO</h1>
        <div class="boxIcones">
          <div class="cardIcons">
            <img src="../../assets/secao3/checklist.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Entregas</p>
              <p>
                Acompanhe cada encomenda que chega. <br />
                Para retirar, use assinatura digital via app.
              </p>
            </div>
          </div>

          <div class="cardIcons">
            <img src="../../assets/secao3/carregar.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Recorrente</p>
              <p>
                Convites liberados para visita recorrente. <br />
                Você escolhe o dia e a hora.
              </p>
            </div>
          </div>
          <div class="cardIcons">
            <img src="../../assets/secao3/qrcode.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">QR Code/ FACIAL</p>
              <p>
                Libera a entra e saída de visitas <br />e prestadores de
                serviços.
              </p>
            </div>
          </div>
          <div class="cardIcons">
            <img src="../../assets/secao3/carregar.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Recorrente</p>
              <p>
                Convites liberados para visita recorrente. <br />
                Você escolhe o dia e a hora.
              </p>
            </div>
          </div>
          <div class="cardIcons">
            <img src="../../assets/secao3/carregar.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Recorrente</p>
              <p>
                Convites liberados para visita recorrente. <br />Você escolhe o
                dia e a hora.
              </p>
            </div>
          </div>
        </div>

        <!--  
        <div class="box-descricao">
          <h2>
            Nossa maior missão é diminuir <br />
            burocracias, lentidão e falta de <br />
            comunicação. <br />
          </h2>
          <p>Chegou o seu momento de entrar em uma nova Era.</p>
          <div class="btn-conteudo">
            <span>#LIVOspace</span> Conecte seu condomínio.
          </div>
        </div> -->
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
#section2 {
  background: none;
  margin: 0;
  margin-top: -6px;
  padding: 0;
}

.background {
  margin: 0;
  padding: 0;
  width: 100%;
}

.conteudo {
  position: absolute;
  top: -50px;
  width: 100%;
  height: 100%;
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
  font-size: 5.5vw;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 25vw;
}

.boxIcones {
  /* background: red; */
  width: 100%;
  height: 500px;
  padding: 0 12vw;
  top: -80px;
}

.cardIcons {
  /* background: red; */
  width: 50%;
  display: flex;
  margin-top: 15px;
  height: 7vw;
}

.cardIcons img {
  margin: 0;
  padding: 0;
  width: 65px;
  margin-right: 25px;
}
.cardIcons div {
  /* background: red; */
}
.cardIcons p {
  margin: 0;
  padding: 0;
  font-size: 1.6vw;
  font-weight: 400;
  line-height: 1.2em;
}
.titulo_cardIcons {
  font-weight: 600 !important;
  font-size: 1.6vw !important;
  margin-bottom: 5px !important;
}

.box-descricao {
  padding: 0 20em;
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
  width: 45vw;
  border-radius: 80px;
  font-size: 2.5vw;
}

.btn-conteudo span {
  margin-left: 25px;
  margin-right: 5px;
  font-weight: 600;
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
    margin-top: 120px;
    position: relative;
  }
  .conteudo {
    position: absolute;
    top: 57vw;
    width: 100%;
    height: 67.8%;
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
}
</style>
