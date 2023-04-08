<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- 全局注册：直接引用 -->
  <!-- <hello-world></hello-world> -->

  <!-- 局部注册：需要按照1、2、3引用 -->
  <!-- 1 -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
// 2
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // 3
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
  color: #2c3e50;
  margin-top: 60px;
}
</style>
