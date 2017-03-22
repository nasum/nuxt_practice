<template>
  <section class="container">
    <img src="../assets/img/logo.png" alt="Nuxt.js Logo" class="logo" />
    <h1 class="title">
      Universal Vue.js Application Framework
    </h1>
    <nuxt-link class="button" to="/about">
      About page
    </nuxt-link>
    <nuxt-link class="button" to="/test">
      test
    </nuxt-link>
    <button @click="$store.commit('increment')">{{ $store.state.counter }}</button>
  </section>
</template>

<style scoped>
.title
{
  margin: 50px 0;
}
</style>
