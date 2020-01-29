<template>
  <nav class="flex justify-between items-center px-4 py-2 text-white">
    <router-link tag="a" :to="{ name: 'home'}">
      <img class="h-12" src="../../assets/images/logo.svg" />
    </router-link>
    <router-link tag="a" :to="{ name: 'login' }" class="login">Login</router-link>
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
</style>