<template>
  <div class="home">
    <link rel="stylesheet" href="bower_components/chartist/dist/chartist.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <h1 class="animate__animated animate__heartBeat">Animation!</h1>
    <h2 class="animate__animated animate__fadeIn">Dat Jello dough.</h2>

    <div class="ct-chart ct-perfect-fourth"></div>

    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<style>
.animate__animated.animate__heartBeat {
  --animate-duration: 5s;
}

.animate__animated.animate__fadeIn {
  --animate-duration: 5s;
}
</style>
