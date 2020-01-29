<template>
  <div id="app" class="h-full flex flex-col">
    <header v-if="$route.name !== 'home'">
      <Navbar class="bg-blue-std" />
    </header>
    <router-view class="flex-1" />
    <Footer />
  </div>
</template>
<script>
import Navbar from '@/components/partials/Navbar.vue'
import Footer from '@/components/partials/Footer.vue'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>
<style>
@import './assets/style/tailwind.css';
</style>
