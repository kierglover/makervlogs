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

body {
  max-width: 100vw!important;
}

.row {
  display: flex;
  flex-wrap: nowrap;
  -webkit-overflow-scrolling: touch;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
  &::-webkit-scrollbar {
    display: none;
  }
}

</style>
