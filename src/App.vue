<template>
  <div id="app" ref="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to 黄金帅"/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HelloWorld msg="Welcome to 张瑞1 Vue.js App"/>
    <HelloWorld msg="Welcome to 张瑞2 Vue.js App"/>
    <HelloWorld msg="Welcome to 圆头圆脑圆肚皮黄金帅 Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
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
  /* background-color: red; */
}
</style>
