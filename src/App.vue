<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Hello World"/>
    <img alt="Vue logo" src="./assets/logoRe.png">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font: italic 1.2rem "Fira Sans", serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
