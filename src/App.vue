<template>
  <div id="app">
    <h1 style="text-align: center">Conversor de Moedas</h1>
    <div class="line">
      <Conversor moeda-a="USD" moeda-b="BRL"/>
      <Conversor moeda-a="BRL" moeda-b="USD"/>
    </div>
    <div class="line">
      <Conversor moeda-a="CAD" moeda-b="BRL"/>
      <Conversor moeda-a="BRL" moeda-b="CAD"/>
    </div>
    <div class="line">
      <Conversor moeda-a="EUR" moeda-b="BRL"/>
      <Conversor moeda-a="BRL" moeda-b="EUR"/>
    </div>
    <div class="line">
      <Conversor moeda-a="GBP" moeda-b="BRL"/>
      <Conversor moeda-a="BRL" moeda-b="GBP"/>
    </div>
    <div class="line">
      <Conversor moeda-a="UYU" moeda-b="BRL"/>
      <Conversor moeda-a="BRL" moeda-b="UYU"/>
    </div>
    <div class="line">
      <Conversor moeda-a="ARS" moeda-b="BRL"/>
      <Conversor moeda-a="BRL" moeda-b="ARS"/>
    </div>
  </div>
</template>

<script>

import Conversor from "./components/Conversor.vue"

export default {
  name: 'app',
  components: {
    Conversor
  }
}
</script>

<style>
#app {
  margin: auto;
  max-width: 900px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

.line{
  margin-top: 40px;
  display: flex;
  justify-content: space-around;
}
</style>
