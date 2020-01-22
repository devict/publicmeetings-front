<template>
  <div id="app">
    <router-view class="router-view" />
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
#app {
  height: 100%;
  display: flex;
  flex-direction: column;
}
.router-view {
  flex: 1 1 0%;
}
</style>
