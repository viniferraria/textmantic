<template>
  <div id="app">
    <img title="eid sucks" alt="Textmantic logo" src="./assets/logo.gif">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <TextField></TextField>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import TextField from './components/TextField'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    TextField
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
