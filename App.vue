<template>
  <img alt=" " src="./github.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Header />
  <Components />
  <Assets/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
  font-size: 1rem;
}
</style>
