<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld/>
    <InputMaskTel/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import InputMaskTel from './components/InputMaskTel.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, 
    InputMaskTel
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
