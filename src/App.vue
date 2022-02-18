<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ilMioComponente></ilMioComponente>
    <componenthero></componenthero>
  </div>
</template>

<script>
import ilMioComponente from './components/ilMioComponente.vue'
import componenthero from './components/componenthero.vue'

export default {
  name: 'App',
  components: {
    ilMioComponente,
    componenthero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
