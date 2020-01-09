<template>
  <div id="app">
    <router-view />
    <Footer />
  </div>
</template>
<script>
import Footer from '@/components/partials/Footer.vue'

export default {
  components: {
    Footer
  }
}
</script>
<style>
@import './assets/style/main.css';
</style>
