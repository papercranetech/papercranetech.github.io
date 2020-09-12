<template>
  <div id="app">

    <!-- <div class="border border-gray-500 rounded w-1/2">Hello</div> -->
    <coming-soon text="This is component something"/>

  </div>
</template>

<script>
import ComingSoon from './components/ComingSoon.vue'

export default {
  name: 'app',
  components: {
    ComingSoon
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
