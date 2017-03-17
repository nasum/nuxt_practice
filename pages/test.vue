<template>
  <section class="test">
    <h1 class="title">
      Test
    </h1>
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
