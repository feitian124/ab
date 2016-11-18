<template>
  <div id="app">
    <art />
    <art />
    <art />
  </div>
</template>

<script>
import Art from './components/Art'

export default {
  name: 'app',
  components: {
    Art
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
