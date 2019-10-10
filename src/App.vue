<template>
  <div id="app">
    <Navbar />
    <Plantillas />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Plantillas from './components/Plantillas.vue'
import Navbar from "./components/Navbar.vue";

export default {
  name: 'app',
  components: {
    Plantillas,
    Navbar
  }
}
</script>

<style>

</style>
