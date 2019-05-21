<template>
  <div id="app">
    <img id="logo" alt="App logo" src="./assets/logo.png">
    <!--Variable used on HelloWorld.vue under as "{{msg}}" between keys-->
    <HelloWorld msg="Welcome to Your Worst Nightmare!"/>
  </div>
</template>

<script>
//component exported from the file under the name defined under export default -> name variable on the script section
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
#logo{
  width: 150px;
}
</style>
