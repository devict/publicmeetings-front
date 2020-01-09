import GenericHeader from '@/components/partials/GenericHeader';
<template>
  <div>
    <GenericHeader />
    <div class="user-profile">
      <div class="container">
        <h1>User Name</h1>
        <div class="flex col-2-container">
          <div class="card w-1/2 col-2">
            <div class="card-title">Details</div>
            <div class="card-container">
              <div>
                <label>Name</label>
                <div>Full Name</div>
              </div>
              <div>
                <label>Email</label>
                <div>youremail@example.com</div>
              </div>
              <div>
                <label>Phone</label>
                <div>(316) 555-5555</div>
              </div>
              <div class="text-right">
                <button class="btn btn-primary" type="button">edit</button>
              </div>
            </div>
          </div>
          <div class="card w-1/2 col-2">
            <div class="card-title">Preferences</div>
            <div class="card-container">something here</div>
          </div>
        </div>
        <div class="flex col-2-container">
          <div class="card w-1/2 col-2">
            <div class="card-title">Meeting Reminders</div>
          </div>
          <div class="card w-1/2 col-2">
            <div class="card-title">Favorited Organizations</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import GenericHeader from '@/components/partials/GenericHeader.vue'
export default {
  components: {
    GenericHeader
  }
}
</script>

<style>
</style>