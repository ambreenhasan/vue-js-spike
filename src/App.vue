<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <!-- <bye></bye> -->
  </div>
</template>

<script>
import Hello from './components/Hello'
// import Bye from './components/Bye'

export default {
  name: 'app',
  components: {
    Hello
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
