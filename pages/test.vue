<template>
  <section class="test">
    <h1 class="title">
      Test
    </h1>
    <nuxt-link class="button" to="/">
      Home page
    </nuxt-link>
  </section>
</template>
<script>
export default {
  data ({ req }) {
    return {
      name: req ? 'server' : 'client'
    }
  }
}
</script>

<style scoped>
</style>
