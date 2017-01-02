<template>
  <section id="app" class="hero is-fullheight">
    <div class="hero-body">
      <div class="container">
        <img src="./assets/logo.png">
        <h1 class="title is-1">{{ msg }}</h1>
        <h2 class="subtitle is-2">Happy coding!</h2>
      </div>
    </div>
  </section>

</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to the Vue.js + Bulma Starter'
    }
  }
}
</script>

<style>

#app {
  text-align: center;
}

</style>
