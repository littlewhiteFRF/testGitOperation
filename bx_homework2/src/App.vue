<template>
  <div id="app">
    <bxHomework/>
    <!--<img src="./assets/logo.png">-->
  </div>
</template>

<script>
import bxHomework from './components/bxHomework'

export default {
  name: 'App',
  components: {
    bxHomework
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
