<template>
  <div id="app">
    <h1 style="text-align: center">Currency Conversor</h1>
    <div class="line">
      <Conversor currency-a="USD" currency-b="BRL"/>
      <Conversor currency-a="BRL" currency-b="USD"/>
    </div>
    <div class="line">
      <Conversor currency-a="CAD" currency-b="BRL"/>
      <Conversor currency-a="BRL" currency-b="CAD"/>
    </div>
    <div class="line">
      <Conversor currency-a="EUR" currency-b="BRL"/>
      <Conversor currency-a="BRL" currency-b="EUR"/>
    </div>
    <div class="line">
      <Conversor currency-a="GBP" currency-b="BRL"/>
      <Conversor currency-a="BRL" currency-b="GBP"/>
    </div>
    <div class="line">
      <Conversor currency-a="UYU" currency-b="BRL"/>
      <Conversor currency-a="BRL" currency-b="UYU"/>
    </div>
    <div class="line">
      <Conversor currency-a="ARS" currency-b="BRL"/>
      <Conversor currency-a="BRL" currency-b="ARS"/>
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
