<template>
  <div id="app">
      <img src="./img/vuelogo.png" alt="logo" height="100px">
      <h1>Calculadora</h1>
      <Calculator />
  </div>
</template>

<script>
import Calculator from "./main/Calculator"

export default {
    components: { Calculator }
}
</script>

<style>
@font-face {
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-Thin.ttf");
}

*{
    font-family: "RobotoMono", monospace;
}

body {
    margin: 0;
}

#app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: #fff;
    background: linear-gradient(to right, rgb(31, 64, 55), rgb(153, 242, 200));
}
</style>