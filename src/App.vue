<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <div>mvpme82</div>
  <MyNewComp />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyNewComp from "./components/MyNewComp.vue";

export default {
  name: "App",
  components: { HelloWorld, MyNewComp },
};
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
