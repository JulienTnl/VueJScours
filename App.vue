<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Calculette/>
    <Majuscules/>
    <convertisseur/>
    <br/>
    <br/>
    <Todolist/>
    <Carroussel/>
  </div>
</template>

<script>
import Calculette from './components/Calculette.vue'
import Majuscules from './components/Majuscules.vue'
import convertisseur from './components/convertisseur.vue'
import Todolist from './components/Todolist.vue'
import Carroussel from './components/Carroussel.vue'

export default {
  name: 'App',
  components: {
    Calculette,
    Majuscules,
    convertisseur,
    Todolist,
    Carroussel,

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
