<template>
  <div id="app" class="main-app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  color: #2c3e50;
}
.main-app{
  height: 100%;
  width: 100%;
}
html,body{
  height: 100%;
  width: 100%;
// background-color: #F5F5F5;
}
</style>
