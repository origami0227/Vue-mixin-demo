<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
  </div>
</template>

<script>
import log from './mixins/log'
export default {
  name: "App",
  mixins: [log],
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
