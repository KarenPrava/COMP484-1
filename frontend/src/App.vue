<template>
  <div id="app">
    <div>
      <navbar></navbar>
    </div>
    <div>
      <router-view/>
    </div>
  </div>
</template>

<script>
import Navbar from './views/Navbar.vue';
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
