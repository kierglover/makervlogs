<template>
    <div class="video">
        <h5> {{VideoTitle}} </h5>
        <iframe width="560" height="315" v-bind:src="VideoLink" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <p>{{VideoInfo}}</p>
    </div>
</template>

<script>

export default {
  name: 'Video',
  components: {
  },
  props: [
      'VideoTitle',
      'VideoLink',
      'VideoInfo'
  ]
}

</script>

<style lang="sass" scoped>

.video {
    max-width: 50vw;
    padding-right: 3em;
}

</style>


