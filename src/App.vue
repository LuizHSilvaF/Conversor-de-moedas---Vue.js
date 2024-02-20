<template>
  <div id="app">
    <ConversorMoeda moedaA="USD" moedaB="BRL"/>
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
}
</style>
