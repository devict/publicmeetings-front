<template>
  <div>
    <HomeHeader />
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
import HomeHeader from '@/components/partials/HomeHeader.vue'

export default {
  name: 'home',
  components: {
    HomeHeader,
    Schedule,
    About
  }
}
</script>
<style scoped>
.about {
  background: url('../assets/images/seats.jpg');
  background-position: center;
  background-size: cover;
  color: white;
  padding-top: 4rem;
  padding-bottom: 4rem;
  text-align: center;
  text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.3);
}

.about p {
  text-align: left;
}
</style>