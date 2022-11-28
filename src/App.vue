<template>
  <div id="app">
    <HeaderNav/>
    <corpoCentrale/>
    <FooterLinks/>
  </div>
</template>

<script>
import HeaderNav from './components/Header.vue'
import corpoCentrale from './components/Corpo.vue'
import FooterLinks from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HeaderNav,
    corpoCentrale,
    FooterLinks
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
