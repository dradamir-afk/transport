<template>
  <div id="app">
    <AuthoPage></AuthoPage>
  </div>
</template>

<script>
import AuthoPage from './components/AuthoPage.vue'

export default {
  name: 'App',
  components: {
    AuthoPage
  }
}
</script>

<style>
body{
  width: 100%;
  height:100%;
  margin:auto;
  background-color: #edf1fd;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
