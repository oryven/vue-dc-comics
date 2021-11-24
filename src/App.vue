<template>

  <div id="app">
    <Myheader/>
    <Content/>
    <Loghi/>
    <Footer/>
    <Social/>
  </div>

</template>

<script>
import Myheader from './components/Myheader.vue'
import Content from './components/Content.vue'
import Loghi from './components/Loghi.vue'
import Footer from './components/Footer.vue'
import Social from './components/Social.vue'

export default {
  name: 'App',
  components: {
    Myheader,
    Content,
    Loghi,
    Footer,
    Social
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
