<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/elixir_logo.png">
    <AboutElixir msg="functional - dynamic - scalable"/>
  </div>
</template>

<script>
import AboutElixir from './components/AboutElixir.vue'

export default {
  name: 'App',
  components: {
    AboutElixir
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
  width: 100%;
}
</style>
