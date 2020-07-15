<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <Hero />
  </div>
</template>

<script>
import Hero from './components/hero-section'

export default {
  name: "App",
  components: {
    Hero
  }
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
img {
  margin: 0; padding: 0;
  top: 10px;
}
</style>
