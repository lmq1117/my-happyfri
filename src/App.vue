<template>
  <div id="app">
    <img v-bind:title="message" src="./assets/logo.png">
    {{ message }}
    <!--<router-view/>-->
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return {
      message:'hello my vue'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
