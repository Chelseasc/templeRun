<template>
  <div id="app">
    <game-container></game-container>
  </div>
</template>

<script>
  import GameContainer from './components/gamecontainer'
  export default {
    components:{
      GameContaier
    },
    name: 'app'
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
