<template>

  <div id="app">
    <Myheader/>
    <Content/>
  </div>

</template>

<script>
import Myheader from './components/Myheader.vue'
import Content from './components/Content.vue'

export default {
  name: 'App',
  components: {
    Myheader,
    Content
  }
}
</script>,

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #505f6d;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
