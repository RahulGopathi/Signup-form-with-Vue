<template>
  <Signup />
</template>

<script>
import Signup from "./components/Signup_form";

export default {
  name: "App",
  components: { Signup },
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

body {
  margin: 0px;
  background: #eee;
}
</style>
