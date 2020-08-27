<template>
<body>
  <div id="app">
    <counter msg />
  </div>
</body>
</template>

<script>
import counter from "./components/counter.vue"

export default {
  name: "App",
  components: {
   counter,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding: 3em;
}
body { 
  background-image: url("./assets/1.jpg"); 
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>