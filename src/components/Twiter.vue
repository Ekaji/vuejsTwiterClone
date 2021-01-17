<template>
  <div class='text-elephant-50 '>
    <info />
    <home />
    <!-- <trends /> -->
    <navigation />
  </div> 
</template>

<script>
import Home from './home/Home.vue'
import Navigation from './navigation/Navigation.vue'
import Info from './info/Info'
// import Trends from './trends/Trends.vue'

export default {
  name: 'Twiter',
  components: {
    Home,
    Navigation,
    Info,
    // Trends
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
