<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Case1 />
  <hr>
  <Case2 />
</template>

<script>
// // import HelloWorld from './components/HelloWorld.vue'
import Case1 from './components/Case1.vue'
import Case2 from './components/Case2.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Case1,
    Case2,
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
input {
  width: 320px;
}
</style>
