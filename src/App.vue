<template>
  <div id="app">
    <app-bar />
    <router-view />
  </div>
</template>

<script>
import AppBar from "./components/AppBar";

export default {
  components: {
    "app-bar": AppBar
  }
};
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 48px; /* 为AppBar留的空位 */
}
</style>
