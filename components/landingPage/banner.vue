<template>
  <v-container>
    <v-card flat>
      <v-row align="center" justify="center">
        <v-col cols="12" md="5">
          <v-container>
            <h1 class="display-2 font-weight-black mb-4">
              The Smart Farm Management Software
            </h1>
            <p class="body-1">
              A one stop place for farm management, crop productions, finance,
              resource management, pest monitoring and detection, weather
              forecast, aggregation and lots more.
            </p>
            <div class="my-2">
              <a
                href="https://app.planta.ng/signup"
                style="text-decoration: none;"
                target="_blank"
              >
                <v-btn
                  style="z-index: 1;"
                  x-large
                  color="success"
                  dark
                  depressed
                  tile
                  >Get Started</v-btn
                >
              </a>
              <a
                href="https://demo.planta.ng"
                style="text-decoration: none;"
                target="_blank"
              >
                <v-btn
                  style="z-index: 1;"
                  x-large
                  color="success"
                  dark
                  depressed
                  outlined
                  tile
                  >Click to Preview</v-btn
                >
              </a>
            </div>
            <v-subheader
              >No credit card required. No software to install.</v-subheader
            >
          </v-container>
        </v-col>
        <v-col cols="12" md="6">
          <v-img
            style="z-index: 1;"
            src="https://res.cloudinary.com/musbell/image/upload/v1585361885/Asset2_lrpdn2.png"
          />
        </v-col>
      </v-row>
      <div class="area">
        <ul class="circles">
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'Banner',
}
</script>

<style scoped>
.circles {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.circles li {
  position: absolute;
  display: block;
  list-style: none;
  width: 20px;
  height: 20px;
  background: rgb(144, 199, 62, 0.2);
  animation: animate 25s linear infinite;
  bottom: -150px;
}

.circles li:nth-child(1) {
  left: 25%;
  width: 80px;
  height: 80px;
  animation-delay: 0s;
}

.circles li:nth-child(2) {
  left: 10%;
  width: 20px;
  height: 20px;
  animation-delay: 2s;
  animation-duration: 12s;
}

.circles li:nth-child(3) {
  left: 70%;
  width: 20px;
  height: 20px;
  animation-delay: 4s;
}

.circles li:nth-child(4) {
  left: 40%;
  width: 60px;
  height: 60px;
  animation-delay: 0s;
  animation-duration: 18s;
}

.circles li:nth-child(5) {
  left: 65%;
  width: 20px;
  height: 20px;
  animation-delay: 0s;
}

.circles li:nth-child(6) {
  left: 75%;
  width: 110px;
  height: 110px;
  animation-delay: 3s;
}

.circles li:nth-child(7) {
  left: 35%;
  width: 150px;
  height: 150px;
  animation-delay: 7s;
}

.circles li:nth-child(8) {
  left: 50%;
  width: 25px;
  height: 25px;
  animation-delay: 15s;
  animation-duration: 45s;
}

.circles li:nth-child(9) {
  left: 20%;
  width: 15px;
  height: 15px;
  animation-delay: 2s;
  animation-duration: 35s;
}

.circles li:nth-child(10) {
  left: 85%;
  width: 150px;
  height: 150px;
  animation-delay: 0s;
  animation-duration: 11s;
}

@keyframes animate {
  0% {
    transform: translateY(0) rotate(0deg);
    opacity: 1;
    border-radius: 0;
  }

  100% {
    transform: translateY(-1000px) rotate(720deg);
    opacity: 0;
    border-radius: 50%;
  }
}
</style>
