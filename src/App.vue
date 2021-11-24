<template>
  <div id="app">
    <Myheader/>
  </div>
</template>

<script>
import Myheader from './components/Myheader.vue'

export default {
  name: 'App',
  components: {
    Myheader
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #505f6d;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
