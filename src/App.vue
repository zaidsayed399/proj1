<template>
  
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <home />
  <contact />


  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import home from './components/home.vue'
import contact from './components/contactus.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    home,
    contact,
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
