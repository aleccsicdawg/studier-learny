<template>
  <div id="app">
    <homepage-vue></homepage-vue>
    <router-view class="animated fadeIn"></router-view>
  </div>
</template>

<script>
import HomepageVue from './components/Navbar.vue'

export default {
  components: {
    HomepageVue
  }
}
</script>

<style>
@import url("https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css");
@import url('https://fonts.googleapis.com/css?family=Roboto+Slab');
#app {
  font-family: 'Roboto Slab', serif;
}
</style>
