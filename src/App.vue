<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="brayan"/>
    <hi/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import hi from './components/hi'

export default {
  name: 'app',
  components: {
    HelloWorld,hi
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
