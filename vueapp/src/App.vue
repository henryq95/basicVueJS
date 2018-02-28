<template>
  <div id="app">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css">
    <img src="./assets/logo.png">
    <test msg="Hello"></test>
    <users></users>
    <simpleaudio></simpleaudio>
  </div>
</template>

<script>
import Test from './components/Test'
import Users from './components/Users'
import SimpleAudio from './components/SimpleAudio.vue'


export default {
  name: 'App',
  components: {
    Test, Users, SimpleAudio
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
