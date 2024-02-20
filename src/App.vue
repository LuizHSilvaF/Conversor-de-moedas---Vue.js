<template>
  <div id="app">
    <h1>Conversor de moedas</h1>
    <div class="linha">
      <ConversorMoeda moedaA="USD" moedaB="BRL"/>
      <ConversorMoeda moedaA="BRL" moedaB="USD"/>
    </div>
    <div class="linha">
      <ConversorMoeda moedaA="CAD" moedaB="BRL"/>
      <ConversorMoeda moedaA="BRL" moedaB="CAD"/>
    </div>
    <div class="linha">
      <ConversorMoeda moedaA="EUR" moedaB="BRL"/>
      <ConversorMoeda moedaA="BRL" moedaB="EUR"/>
    </div>
  </div>
</template>

<script>
import ConversorMoeda from "./components/Conversor.vue";
export default {
  name: 'App',
  components: {ConversorMoeda
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  max-width: 900px;
  margin: auto;
}

.linha{
  display: flex;
  justify-content: space-around;
  margin-top: 40px;
}
</style>
