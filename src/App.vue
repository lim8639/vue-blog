<template>
  <div id="app">
    <helloworld/>
  </div>
</template>

<script>
import helloworld from "@/components/helloworld";

export default {
  name: 'App',
  components: {
     helloworld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1d81e1;
  margin-top: 60px;
}
</style>
