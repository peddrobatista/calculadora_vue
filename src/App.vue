<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator/>
  </div>
</template>

<script>
import Calculator from "./main/Calculator.vue"
export default {
  components: {Calculator}
}
</script>

<style>
@font-face {
  font-family: 'Poppins';
  src: url("./fonts/Poppins/Poppins-Medium.ttf");
}
* {
  font-family: 'Poppins', sans-serif;
}
body {
  margin: 0;
}
#app {
  display: flex;
  height: 100vh;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #2c3e50;
}


</style>
