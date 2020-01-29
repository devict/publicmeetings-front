<template>
  <div class="flex h-full w-full justify-center items-center bg-gray-200">
    <form class="w-96 px-12 py-8 border border-gray-300 bg-white">
      <h1 class="text-4xl mb-8 font-bold leading-tight text-blue-900">Log In</h1>
      <div class="mb-6">
        <label class="text-blue-900 text-xs uppercase tracking-wide">Username</label>
        <input class="block border-b w-full" type="text" placeholder="Username" />
      </div>
      <div class="mb-6">
        <label class="text-blue-900 text-xs uppercase tracking-wide">Password</label>
        <input class="block border-b w-full" type="password" placeholder="Password" required />
      </div>
      <div class="flex justify-between items-center text-sm mb-6">
        <div class="flex items-center">
          <input class="h-4 w-4 mr-1" type="checkbox" id="remember-me" />
          <label class="text-gray-600" for="remember-me">Remember me</label>
        </div>
        <a class="underline text-blue-std" href="#">Forgot password?</a>
      </div>

      <div class="flex">
        <button
          type="button"
          class="rounded-sm w-24 text-center mr-4 py-1 bg-blue-std border border-blue-std text-white"
        >Login</button>
        <button
          type="button"
          class="rounded-sm w-24 text-center py-1 border border-blue-std text-blue-std"
        >Sign-up</button>
      </div>
    </form>
  </div>
</template>
<script>
export default {}
</script>

<style scoped>
</style>
