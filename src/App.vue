<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/shopimg.jpg">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
  
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

header {
  display: flex;
  align-items: center;
  padding: 10px 20px;

}
#app {
  position:absolute;
  top:20px;
  left:20px;
  z-index: 10;

  
}
</style>
