<template>
  <div id="app">
  <Candan msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>


import  Candan from './components/Candan'
export default {
  name: 'App',
  components: {
    Candan,
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
