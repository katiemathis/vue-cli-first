<template>
  <div id="app">
    <img alt="Katie Face" src="./assets/Picture1.png">
    <NewComponentTitle></NewComponentTitle>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NewComponentTitle from './components/NewComponentTitle.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NewComponentTitle
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
