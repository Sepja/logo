<template>
  <div id="app">
    <img src="./assets/turtle.png" height="500" width="1000" ra/>
    <LogoView/>
  </div>
</template>

<script>
import LogoView from './components/LogoView.vue'

export default {
  name: 'App',
  components: {
    LogoView
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
  height: 100%;
  width: 100%;
}
</style>
