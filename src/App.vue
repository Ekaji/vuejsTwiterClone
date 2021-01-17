<template >
  <div class='bg-elephant-600 h-screen m-0 p-0'>
    <twiter />
  </div>
</template>

<script>
import Twiter from './components/Twiter.vue'

export default {
  name: 'App',
  components: {
    Twiter
  }
}
</script>

<style>
html, body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
}
</style>
