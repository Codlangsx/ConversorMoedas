<template>
  <div id="app">
    <center><h1>Conversor de Moedas</h1></center>
    <div class="linha">
      <aplicativo moedaA="USD" moedaB="BRL"/>
      <aplicativo moedaA="BRL" moedaB="USD"/>
    </div>
    <div class="linha">
      <aplicativo moedaA="CAD" moedaB="BRL"/>
      <aplicativo moedaA="BRL" moedaB="CAD"/>
    </div>
    <div class="linha">
      <aplicativo moedaA="EUR" moedaB="BRL"/>
      <aplicativo moedaA="BRL" moedaB="EUR"/>
    </div>
  </div>
</template>

<script>
import Aplicativo from './components/Aplicativo.vue'

export default {
  name: 'App',
  components: {
    Aplicativo
  }
}
</script>

<style>

#app {
  
  margin: auto;
  max-width: 800px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  
}
.linha{
        display: flex;
        justify-content: space-around;
        margin-top: 40px;
    }
</style>
