<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <postComponent />
  </div>
</template>

<script>
import postComponent from './components/postComponent.vue'

export default {
  name: 'app',
  components: {
    postComponent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
