<!-- Site desenvolvido pelo Discente Natan Evangelista Rubenich -->
<!--Disciplina Tópicos especias em computação aplicada -->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ProjetoNatanRubenich msg="Bem-vindo ao meu projeto Vue.js"/>
    
  </div>
</template>

<script>
import ProjetoNatanRubenich from './components/ProjetoNatanRubenich.vue'

export default {
  name: 'App',
  components: {
    ProjetoNatanRubenich
  }
}
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
