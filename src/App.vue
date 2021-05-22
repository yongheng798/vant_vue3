<!--
 * @Descripttion: 陈品富写的demo描述
 * @version: 1.0
 * @Author: chenpinfu~陈品富
 * @Date: 2021-05-22 16:40:01
 * @LastEditors: chenpinfu~陈品富
 * @LastEditTime: 2021-05-22 16:51:30
-->
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <home></home>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import home from './views/home'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    home
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
