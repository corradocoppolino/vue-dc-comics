<template>
  <div id="app">

    <header-dc />
    
    <jumbotron />

    <main-content-dc />

    <main-section-dc />

    <footer-link />

    <footer-follow />
    
  </div>
</template>

<script>

import FooterFollow from './components/FooterFollow.vue'
import FooterLink from './components/FooterLink.vue'
import HeaderDc from './components/HeaderDc.vue'
import Jumbotron from './components/Jumbotron.vue'
import MainContentDc from './components/MainContentDc.vue'
import MainSectionDc from './components/MainSectionDc.vue'

export default {
  name: 'App',
  components: {

    HeaderDc,
    MainContentDc,
    MainSectionDc,
    FooterLink,
    FooterFollow,
    Jumbotron
    
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: 'Roboto', sans-serif;
}

</style>
