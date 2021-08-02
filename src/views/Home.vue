<template>
  <div class="home">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <h1 class="animate__animated animate__heartBeat">I'm a frog!</h1>
    <h2 class="animate__animated animate__fadeIn animate__delay-2s">Sup?</h2>
    <h2 class="animate__animated animate__fadeInUpBig animate__delay-5s">Where dem flies at?</h2>

    <div class="ct-chart ct-perfect-fourth"></div>

    <img alt="Frog" src="../assets/frog.jpg" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <h2 class="animate__animated animate__flip">I am mad hungry.</h2>
  </div>
</template>

<style>
img {
  height: 850px;
}
.animate__animated.animate__heartBeat {
  --animate-duration: 5s;
}
.animate__animated.animate__fadeIn {
  --animate-duration: 5s;
}
.animate__animated.animate__fadeInUpBig {
  --animate-duration: 5s;
}
.animate__animated.animate__flip {
  --animate-duration: 30s;
}
</style>
