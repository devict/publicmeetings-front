<template>
  <div>
    <HomeHeader />
    <main class="container">
      <div class="schedule">
        <h2>Upcoming Meetings</h2>
        <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
        <div class="schedule-items">
          <div class="schedule-item">
            <div class="date">
              <div class="day">wednesday</div>
              <div class="number">14</div>
              <div class="month">November</div>
            </div>
            <div class="meeting">
              <div class="info">
                <a href class="organization-link">Wichita City Council</a>
                <div class="title">Some Public Meeting</div>
                <div class="subtitle">More information goes here.</div>
              </div>
              <div class="details">
                <div class="time">@3:00pm</div>
                <div class="address">
                  <div>100 N Main St.</div>
                  <div>Wichita, Kansas</div>
                </div>
              </div>
            </div>
          </div>
          <div class="schedule-item">
            <div class="date">
              <div class="day">wednesday</div>
              <div class="number">14</div>
              <div class="month">November</div>
            </div>
            <div class="meeting">
              <div class="info">
                <a href class="organization-link">Wichita City Council</a>
                <div class="title">Some Public Meeting</div>
                <div class="subtitle">More information goes here.</div>
              </div>
              <div class="details">
                <div class="time">@3:00pm</div>
                <div class="address">
                  <div>100 N Main St.</div>
                  <div>Wichita, Kansas</div>
                </div>
              </div>
            </div>
          </div>
          <div class="schedule-item">
            <div class="date">
              <div class="day">wednesday</div>
              <div class="number">14</div>
              <div class="month">November</div>
            </div>
            <div class="meeting">
              <div class="info">
                <a href class="organization-link">Wichita City Council</a>
                <div class="title">Some Public Meeting</div>
                <div class="subtitle">More information goes here.</div>
              </div>
              <div class="details">
                <div class="time">@3:00pm</div>
                <div class="address">
                  <div>100 N Main St.</div>
                  <div>Wichita, Kansas</div>
                </div>
              </div>
            </div>
          </div>

          <a href="#" class="schedule-link">See Full Schedule &rarr;</a>
        </div>
      </div>
    </main>
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import About from '@/components/partials/About.vue'
import HomeHeader from '@/components/partials/HomeHeader.vue'

export default {
  name: 'home',
  components: {
    HomeHeader,
    About
  }
}
</script>
<style scoped>
@import '../assets/style/pages/home.css';
</style>