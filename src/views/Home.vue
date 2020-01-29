<template>
  <div>
    <header class="relative text-white overflow-hidden text-center">
      <Navbar />
      <div class="container h-full mx-auto -mt-16 text-shadow flex justify-center items-center">
        <div>
          <h1 class="text-5xl font-black">Local Meetings. Stay Informed.</h1>
          <p class="text-2xl mb-4">Sign-up to receive alerts, set reminders, and more</p>
          <a href="/register" class="button">Sign-Up</a>
        </div>
      </div>
      <div class="absolute bottom-0 inset-x-0 -mb-1 -mx-4">
        <svg viewBox="0 0 1436 64" class="fill-current" xmlns="http://www.w3.org/2000/svg">
          <path d="M1436 63.5H0C0 28.43 510 0 718 0s718 28.43 718 63.5z" />
        </svg>
      </div>
    </header>
    <main class="container">
      <Schedule />
    </main>
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import About from '@/components/partials/About.vue'
import Schedule from '@/components/Schedule.vue'
import Navbar from '@/components/partials/Navbar.vue'

export default {
  name: 'home',
  components: {
    Navbar,
    Schedule,
    About
  }
}
</script>
<style scoped>
header {
  background: url('../assets/images/courthouse.jpg');
  background-position: center;
  background-size: cover;
  height: 25rem;
}
</style>