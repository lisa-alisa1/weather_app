<template>
  <div id="app">
    <MainPage />
  </div>
  
</template>

<script>
import MainPage from './views/MainPage.vue';

export default {
  name: 'App',
  components: {
    MainPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
