<template>
  <div id="app">
    <click/>
  </div>
</template>

<script>
import Click from './components/Click.vue'

export default {
  name: 'App',
  components: {
    Click
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
