<template>  
  <div>
    <img alt="Vue logo" src="./assets/logo.png"/>
    <menu-app></menu-app>
  </div>
</template>

<script>

import menu from './components/menu.vue'

export default {
  components: {
    menuApp: menu
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
