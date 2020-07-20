<template>
  <div id="app">
   
    <Banner />
    <Footer />
  </div>
</template>

<script>
import Banner from './components/Banner.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Banner,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
  background-color: #753ff6;
  color:#F8F5FF;
}
*{
  padding: 0;
  margin: 0;
  box-sizing:border-box;
}
</style>
