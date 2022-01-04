<template>
  <HelloWorld msg="Welcome to Your Vue.js App" v-if="false"/>
  <MyChart></MyChart>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyChart from './components/MyChart.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyChart
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
