<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
     <!-- step 3 use -->
    <HeaderComp msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// step 1 import
import HeaderComp from './components/HeaderComp'

export default {
  name: 'App',
  components: {
    // step 2 register
    HeaderComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:rgb(203, 65, 194);
  margin-top: 60px;
}
</style>
