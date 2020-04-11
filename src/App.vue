<template>
  <div id="app">
    <!-- <img width="25%" src="./assets/logo.png">
    <HelloWorld msg="Hello Vue in CodeSandbox!" />
     -->
     <sample/>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld";
import Sample from "./components/Sample"

export default {
  name: "App",
  components: {
    // HelloWorld
    Sample
  }
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
