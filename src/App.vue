<template>
  <div id="app">
    <hello></hello>
    <playlist></playlist>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'
import Playlist from './components/Playlist.vue'

export default {
  name: 'app',
  components: {
    Hello,
    Playlist
  }
}
</script>

<style lang="sass">

.lead {
  font-size: 1.5em;
}

</style>
