<template>
  <div id="app">
    <h1>Calculadora</h1>
    <CalculatorComp />
  </div>
</template>

<script>
import CalculatorComp from './main/CalculatorComp'

export default {
  components: {CalculatorComp}
}
</script>

<style>
@font-face {
  font-family: 'RobotoMono';
  src: url('./fonts/RobotoMono-Thin.ttf')
}

* {
  font-family: 'RobotoMono', monospace;
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
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>