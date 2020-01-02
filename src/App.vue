<template>
  <div id="app">
    <JsSerraBanner />
  </div>
</template>

<script>
import JsSerraBanner from './components/JsSerraBanner.vue'

export default {
  name: 'app',
  components: {
    JsSerraBanner
  }
}
</script>

<style>
html{
  background-color: gray;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 60px; */
  /* width: 800px */
}
</style>
