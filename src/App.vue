<template>
  <div id="app">
    <Plantillas />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Plantillas from './components/Plantillas.vue'

export default {
  name: 'app',
  components: {
    //HelloWorld,
    Plantillas
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
