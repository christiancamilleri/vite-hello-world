<script >
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'


export default {
  data() {
    return {

    }
  },
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<style>
.container {
  text-align: center;
}
</style>
