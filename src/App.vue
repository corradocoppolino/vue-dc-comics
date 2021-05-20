<template>
  <div id="app">

    <header-dc />

    <main-content-dc />

    <main-section-dc />

    <footer-link />
    
  </div>
</template>

<script>

import FooterLink from './components/FooterLink.vue'
import HeaderDc from './components/HeaderDc.vue'
import MainContentDc from './components/MainContentDc.vue'
import MainSectionDc from './components/MainSectionDc.vue'

export default {
  name: 'App',
  components: {
    HeaderDc,
    MainContentDc,
    MainSectionDc,
    FooterLink
    
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}


</style>
