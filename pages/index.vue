<template>
  <section>
    <div class="one">
      <Navbar />
      <div>
        <div class="row">
          <div id="one-a" class="col-md-7">
            <div>
              <h1>A Well-Defined Digital <br> Financial services <br> Company</h1>
              <p class="mt-3">With a drive to offer top-notch solutions using state of <br> the art infrastructures to enhance innovations and help <br> small businesses in Africa to grow globally.</p>
              <button type="button" class="mt-3 btn btn-outline-warning px-5 py-2">EXPLORE</button>
            </div>
          </div>
          <div id="one-b" class="col-md-5">
            <img src="../assets/slide.png" alt="">
          </div>
        </div>
      </div>
    </div>
    <div class="two p-5">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div id="video-container" class="p-4">
              <img class="align-middle" id="play" src="../assets/play.png" alt="">
            </div>
          </div>
          <div class="col-md-6">
            <div id="two-text">
              <h6>The future of digital banking.</h6>
              <h2>Glade Virtual Card.</h2>
              <p>Click to play to see what Glade Virtual card is <br> about and what it does.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="three p-5">
      <div class="container">
        <div class="row pl-3">
          <div class="col-md-7">
            <div id="cards">
              <h6 class="pl-3">Digitally secure your transactions.</h6>
              <h2 class="pl-3">Benefits</h2>
              <img src="../assets/phone.png" alt="">
            </div>
          </div>
          <div class="col-md-5">
            <div id="three-texts" class="pl-4">
              <div>
                <h5>Security and Control</h5>
                <p>Set locked down "to a specified amount or set <br> a credit limit for every payment and your bank <br> account is never exposed</p>
              </div>
              <div class="mt-5 pt-2">
                <h5>FREE of Charge</h5>
                <p>Get access to Glade Virtual cards and services <br> absolutely free and zero charges.</p>
              </div>
              <div class="mt-5 pt-2">
                <h5>One time usage option</h5>
                <p>After every transaction you can instruct your <br> Virtual Card to self Destruct thereby keeping <br> your information safe.</p>
              </div>
              <div class="mt-5 pt-2">
                <h5 id="h5">SEE MORE</h5>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="four p-5">
      <div class="container">
        <div class="row">
          <div class="col-md-6 pt-5">
            <div class="mt-5 pt-5">
              <div class="ml-4">
                <h6>The Future of Digital Banking</h6>
                <h2>Frequently asked <br>Questions</h2>
              </div>
            </div>
          </div>
          <div class="col-md-6 pt-5">
            <div class="mt-3">
              <div role="tablist">
                <b-card no-body class="mb-1">
                  <b-card-header header-tag="header" style="background-color: white; border-bottom: none" class="p-1" role="tab">
                    <b-button block v-b-toggle.accordion-1 variant="transparent"><h5 style="font-size: 900">What is the Virtual prepaid Credit Card?</h5></b-button>
                  </b-card-header>
                  <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
                    <b-card-body>
                      <b-card-text><small>{{ one }}</small></b-card-text>
                    </b-card-body>
                  </b-collapse>
                </b-card>
                <b-card no-body class="mb-1">
                  <b-card-header header-tag="header" style="background-color: white; border-bottom: none" class="p-1" role="tab">
                    <b-button block v-b-toggle.accordion-2 variant="transparent"><h5 style="font-size: 900">How can i purchase the Glade Virtual Card</h5></b-button>
                  </b-card-header>
                  <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
                    <b-card-body>
                      <b-card-text><small>{{ two }}</small></b-card-text>
                    </b-card-body>
                  </b-collapse>
                </b-card>
                <b-card no-body class="mb-1">
                  <b-card-header header-tag="header" style="background-color: white; border-bottom: none" class="p-1" role="tab">
                    <b-button block v-b-toggle.accordion-3 variant="transparent"><h5 style="font-size: 900">What can i receive the number of my Card?</h5></b-button>
                  </b-card-header>
                  <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
                    <b-card-body>
                      <b-card-text><small>{{ three }}</small></b-card-text>
                    </b-card-body>
                  </b-collapse>
                </b-card>
                <b-card no-body class="mb-1">
                  <b-card-header header-tag="header" style="background-color: white; border-bottom: none" class="p-1" role="tab">
                    <b-button block v-b-toggle.accordion-3 variant="transparent"><h5 style="font-size: 900">Is it acceptable world wide</h5></b-button>
                  </b-card-header>
                  <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
                    <b-card-body>
                      <b-card-text><small>{{ four }}</small></b-card-text>
                    </b-card-body>
                  </b-collapse>
                </b-card>
              </div>
              <!-- Accordion  -->
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="five p-5">
      <div class="text-center mt-3">
        <h2 id="h2">Get a Gladepay Virtual Card</h2>
        <p>Sign up and enjoy all our benefits. Its Free, Simple and Easy.<br> Get it today</p>
        <button type="button" class="btn btn-warning px-5 py-3"><h6>GET YOUR CARD FREE</h6></button>
      </div>
    </div>
    <footer class="p-5">
      <div class="mt-4">
        <div class="container">
          <div class="row">
            <div class="col-md-3">
              <p>Glades designed and operates the website and app. It is a trading name of GladePay Technology Limited</p>
            </div>
            <div class="col-md-3">
              <h6>Newsletter</h6>
              <p>Sign up for alerts, special offers, news, education and updates.</p>
              <div id="newsletter" class="px-4 py-2">
                <p>gladepayvirtual@xyz.com<span>GO</span></p>
              </div>
            </div>
            <div class="col-md-3">
              <p>Terms and conditions</p>
              <p>Privacy policy</p>
              <p>Contact Us</p>
            </div>
            <div class="col-md-3">
              <div>
                <span>
                  <img style="width:100px" height="auto" src="../assets/appstore.svg" alt="">
                </span>
                <span>
                  <img style="width:100px" height="auto" src="../assets/playstore.svg" alt="">
                </span>
              </div>
              <div>
                <span>
                  <img style="width:65px" height="auto" src="../assets/mastercard.svg" alt="">
                </span>
                <span>
                  <img style="width:65px" height="auto" src="../assets/pci.svg" alt="">
                </span>
                <span>
                  <img style="width:65px" height="auto" src="../assets/visa.svg" alt="">
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <hr class="mt-3 col-md-10 mx-auto">
      <div class="text-center mt-3">
        <h5 id="footer-note">2020 GladePayDigital</h5>
      </div>
    </footer>
  </section>
</template>

<script>
import Navbar from '~/components/Navbar'
export default {
  components: {
    Navbar
  },
  data() {
      return {
        one: `Glade Virtual Card is free, to access simply sign up and create an account here`,
        two: `Glade Virtual Card is free, to access simply sign up and create an account here`,
        three: `Glade Virtual Card is free, to access simply sign up and create an account here`,
        four: `Glade Virtual Card is free, to access simply sign up and create an account here`
      }
    }
}
</script>

<style scoped>
.one {
  width: 100%;
  height: auto;
  background-image: url('../assets/man.png');
  background-size: cover;
  background-repeat: no-repeat;
}

#one-a {
  margin-top: 8%;
  padding-left: 7%;
}

#one-a h1 {
  font-size: 3.4rem;
}

#one-a p {
  color: #77869e;
}

#one-a button {
  background-color: #ff6f00;
  border-radius: 30px;
  color: white;
}

h1 {
  font-weight: 700;
  color: #0d3e53;
}

#one-b {
  width: 100%;
  z-index: 1;
}

img {
  width: 100%;
  height: auto;
}

.two {
  width: 100%;
  height: 100vh;
}

#video-container {
  background-image: url('../assets/woman.png');
  background-size: cover;
  background-repeat: no-repeat;
  width: 100%;
  height: 100%;
}

#video-container #play {
  width: 10%;
  height: auto;
  margin: 0 auto;
  text-align: center;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  align-content: center;
  position: relative;
  margin-top: 35%;
}

#two-text {
  margin-top: 30%;
  margin-bottom: 30%;
  margin-left: 8%;
}

#two-text h6 {
  font-weight: 700;
}

#two-text h2 {
  font-weight: 700;
  color: #00afef;
}

#two-text p {
  color: #939fb2;
}

.three {
  width: 100%;
  height: auto;
  background-color: #f8fdff;
}

#cards h6 {
  font-weight: 700;
}

#cards h2 {
  font-weight: 700;
  color: #00afef;
}

#three-texts {
  margin-top: 15%;
}

#three-texts h5 {
  font-weight: 700;
}

#h5 {
  font-weight: 400;
  color: #00afef;
}

#three-texts p {
  color: #929fb2;
}

#four h6 {
  font-weight: 700;
}

h5 {
  font-size: 700;
}

.four h2 {
  font-weight: 800;
  color: #00afef;
}

.five {
  background-color: #f8fdff;
}

.five #h2 {
  font-size: 700;
  color: #00afef;
}

.five p {
  color: #939fb2;
}

.five button {
  background-color: #00afef;
  border: #00afef;
  border-radius: 30px;
  color: white;
  font-size: 700;
}

.five button:hover {
  border: #00afef;
}

footer {
  background-color: #0a182d;
  color: #7a828d;
  font-size: 0.8rem;
}

footer h6 {
  color: white;
}

#newsletter {
  background-color: white;
  color: #77869e;
  border-radius: 30px;
}

#newsletter p span {
  border-left: #7a828d 1px solid;
  padding-left: 2%;
  margin-left: 3%;
  color: #00afef;
  font-size: 1rem;
  font-weight: 700;
}

hr {
  color: #77869e;
  background-color: #77869e;
}

#footer-note {
  font-weight: 100;
}
</style>