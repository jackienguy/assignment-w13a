<template>
  <div id="app">
    <vue-header></vue-header>
    <img alt="Vue logo" src="./assets/logo.png">
    <vue-body></vue-body>
    <vue-footer></vue-footer>
  </div>
</template>

<script>
import VueHeader from './components/VueHeader.vue'
import VueBody from './components/VueBody.vue'
import VueFooter from './components/VueFooter.vue'




export default {
  name: 'App',
  components: {
    // VueHeader,
    VueBody,
    VueHeader,
    VueFooter
   
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
