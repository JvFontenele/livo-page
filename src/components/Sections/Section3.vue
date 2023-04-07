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
            <img src="../../assets/secao3/vinho.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Reservas</p>
              <p>
                É muito facíl reservar um espaço<br />
                com LIVO, basta dois cliques.
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
            <img src="../../assets/secao3/moto.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Delivery</p>
              <p>
                Adiante sua portaria avisando que você <br />
                aguarda delivery ou algum motorista.
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
            <img src="../../assets/secao3/jornal.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Mural</p>
              <p>
                Informações compartilhadas. Sobre<br />
                qualquer tipo de evento no condomínio.
              </p>
            </div>
          </div>
          <div class="cardIcons">
            <img src="../../assets/secao3/calendario.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Eventos</p>
              <p>
                Múltiplos convites para substituir<br />
                a clássica lista da festa.
              </p>
            </div>
          </div>
          <div class="cardIcons">
            <img src="../../assets/secao3/patinha.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">PET</p>
              <p>Seu pet com cadastro.</p>
            </div>
          </div>
          <div class="cardIcons">
            <img src="../../assets/secao3/placa.svg" alt="" />
            <div>
              <p class="titulo_cardIcons">Ocorrências e Enquetes</p>
              <p>
                Em tempo real perceba a temperatura<br />
                de intenções. No WhatsApp tudo<br />
                se perde... Organize melhor o que<br />
                o condomínio precisa.<br />
              </p>
            </div>
          </div>
        </div>

        <div class="boxBtn">
          <img
            class="botao"
            src="../../assets/secao3/botaoparabaixo.svg"
            alt=""
          />
        </div>
        <div class="box-card">
          <div class="card">
            <img src="../../assets/secao3/celular.svg" alt="" />
            <div>
              <p class="titulo_card">App do proprietário</p>
              <p>
                Residencial e comercial. <br />
                Livo é intuitivo e simples de usar, igual <br />
                pedir comida no ifood ou mandar um <br />
                arquivo pelo WhatsApp. <br />
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../../assets/secao3/celular1.svg" alt="" />
            <div>
              <p class="titulo_card">Visitante e prestador</p>
              <p>
                Cadastro rápido e seguro seguindo<br />
                nossa LGPD.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../../assets/secao3/globo.svg" alt="" />
            <div>
              <p class="titulo_card">LIVO web</p>
              <p>
                Prático para quem usa no dia a dia,<br />
                para as equipes nas portarias<br />
                acessarem sem muitos cliques ou<br />
                várias telas.<br />
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../../assets/secao3/relatorio.svg" alt="" />
            <div>
              <p class="titulo_card">LIVO relatórios</p>
              <p>
                Para gerentes e síndicos<br />
                acompanharem a estatística geral<br />
                por meio de dados. Formato Power BI.<br />
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
  top: -40px;
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
  height: 20vw;
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

.boxIcones {
  /* background: red; */
  width: 100%;
  height: 40vw;
  padding: 0 12vw;
  top: -80px;
  /* background: red; */
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr;
}

.cardIcons {
  width: 100%;
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

.cardIcons p {
  font-family: "ArticulatCF";
  margin: 0;
  padding: 0;
  font-size: 1.6vw;
  font-weight: 400;
  line-height: 1.2em;
}
.titulo_cardIcons {
  font-weight: 400 !important;
  font-size: 1.9vw !important;
  margin-bottom: 5px !important;
}

.box-descricao {
  padding: 0 20em;
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
.boxBtn {
  /* background: rebeccapurple; */
  text-align: center;
}
.botao {
  width: 7vw;
}

.box-card {
  /* background: red; */
  width: 100%;
  height: 20vw;
  display: flex;
  padding: 10vw;
  margin-top: 5vw;
  justify-content: space-around;
  align-items: center;
}
.card {
  background: rgba(202, 110, 237, 0.6);
  height: 20vw;
  width: 15vw;
  border-radius: 20px;
  text-align: center;
  padding: 10px;
}

.card div {
  text-align: start;
}
.card p {
  font-size: 0.79vw;
  margin: 0;
}
.titulo_card {
  font-weight: 500;
  font-size: 1.2vw !important;
  margin: 0 0px 5px 0px !important;
}
.card img {
  width: 80px;
  margin: 1vw 0 2vw 0;
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
