<template>
  <div id="app">
    <NavBar msg="Welcome to Your Vue.js App"/>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Carousel msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Carousel from './components/Carousel.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Carousel
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
}
</style>
