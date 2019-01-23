<template>
    <div class="playlist">
        <h3>Featured Makervlogs</h3>
        <div class="row">
            <player video-title="Codeless Startup in 24hrs" video-link="https://www.youtube.com/embed/LAdxiQ05e40" video-info="You don't need to code to launch 🚀 Take a look at how 🎨 designer 💻 developer and 🛠 maker Kieran Glover launched an idea in 24hrs using codeless tech like Webflow 🤘"></player>
            <player video-title="Testing Props" video-link="https://www.youtube.com/embed/LAdxiQ05e40" video-info="You don't need to code to launch 🚀 Take a look at how 🎨 designer 💻 developer and 🛠 maker Kieran Glover launched an idea in 24hrs using codeless tech like Webflow 🤘"></player>
        </div>
        <h3>Upcoming Makervlogs</h3>
        <div class="row">
            <player video-title="Codeless Startup in 24hrs" video-link="https://www.youtube.com/embed/LAdxiQ05e40" video-info="You don't need to code to launch 🚀 Take a look at how 🎨 designer 💻 developer and 🛠 maker Kieran Glover launched an idea in 24hrs using codeless tech like Webflow 🤘"></player>
            <player video-title="Testing Props" video-link="https://www.youtube.com/embed/LAdxiQ05e40" video-info="You don't need to code to launch 🚀 Take a look at how 🎨 designer 💻 developer and 🛠 maker Kieran Glover launched an idea in 24hrs using codeless tech like Webflow 🤘"></player>
        </div>
    </div>
</template>

<script>
import Player from './Player.vue'

export default {
  name: 'Playlist',
  components: {
      Player
  }
}
</script>

<style lang="sass" scoped>

.playlist {
    padding-left: 3em;
}

</style>
