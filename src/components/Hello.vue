<template>
  <div class="hero container">
    <h1 class="hero__title">Welcome to 🎥 Makervlogs</h1>
    <p class="hero__lead">Makervlogs helps fellow indie makers learn, grow and and make it happen with highly curated Makervlogs!</p>
    <p></p>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang='sass' scoped>

@mixin hero-padding {
  padding: 0em 15em 0em 15em;
}

.hero {
  @include hero-padding;
  &__title {
    text-align: center;
  }
  &__lead {
    text-align: center;
    font-size: 1.5em;
  }
}


</style>
