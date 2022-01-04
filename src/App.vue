<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
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
#app{
  width: 100vw;
  height: 100vh;
}
*{
  margin: 0;
  padding: 0;
}
html,body{
  margin: 0;
  padding: 0;
}
</style>
