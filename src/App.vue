<template>
  <div id="app">
  
  <Department></Department>
 
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Department from './components/Department.vue'

export default {
  name: 'App',
  components: {
   // HelloWorld
    Department
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
