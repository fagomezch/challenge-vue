<template>
  <div id="app">
    <TextScrambler msg="Text Scrambler"/>
    
  </div>
</template>

<script>
import TextScrambler from './components/TextScrambler.vue'

export default {
  name: 'App',
  components: {
    TextScrambler
  }
}
</script>

<style>
body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  align-items: center;
  background-color: #c6c2fa;
  color: #ffffff;
  display: flex;
  height: 100vh;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
