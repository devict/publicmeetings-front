<template>
  <div>
    <GenericHeader />
    <div class="org-profile">
      <div class="container">
        <router-link class="back text-white" :to="{name: 'home'}">&larr; Back</router-link>
      </div>
      <div class="container">
        <h1>Organization Name</h1>
        <p>Vinyl offal roof party selvage ugh tousled. Ramps brunch kickstarter adaptogen hot chicken crucifix post-ironic, snackwave stumptown helvetica distillery normcore narwhal chartreuse. Gastropub cardigan kitsch gentrify typewriter scenester VHS meggings roof party cornhole lomo farm-to-table. Hella vexillologist photo booth four dollar toast chartreuse godard polaroid crucifix you probably haven't heard of them selfies.</p>
        <p>Art party hashtag tilde hella master cleanse. Chicharrones meggings seitan freegan 90's selfies pinterest food truck. Narwhal pitchfork intelligentsia authentic marfa cray, succulents meggings vexillologist semiotics snackwave vice ramps. Wayfarers green juice bespoke cliche roof party. La croix listicle marfa neutra. Raclette iceland poke kickstarter.</p>
        <p>Letterpress asymmetrical typewriter, neutra pour-over pabst direct trade chartreuse air plant +1. Neutra migas thundercats, irony sriracha swag helvetica. Venmo skateboard woke hella helvetica XOXO brunch meggings green juice fingerstache trust fund vaporware bushwick. Pug everyday carry wolf tumblr chambray bitters farm-to-table irony put a bird on it gentrify bespoke sartorial chillwave marfa. Cloud bread brunch locavore, bicycle rights man bun VHS lyft retro pug.</p>
      </div>
    </div>
    <Schedule />
  </div>
</template>

<script>
import GenericHeader from '@/components/partials/GenericHeader'
import Schedule from '@/components/Schedule'
export default {
  components: {
    GenericHeader,
    Schedule
  }
}
</script>

<style scopes>
.org-profile {
  background: #015579;
  color: #fff;
  padding: 1rem 0;
  border-bottom: 1px solid #ccc;
}

.back {
  margin-bottom: 1rem;
}
</style>