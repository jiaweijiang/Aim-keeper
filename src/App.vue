<template>
  <div id="app">
    <mycheckin></mycheckin>
    <!-- <router-view></router-view> -->
  </div>
</template>

<script>
import mycheckin from './components/myCheckIn';

export default {
  name: 'app',
  components: {
    mycheckin
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 0;
  margin: 0;
  color: white;
}
</style>
