<template>
  <div id="app" style="background-image: url('image/2.jpg');">
    <HelloWorld msg="The Infinity War" />
    <div class="col-6"><counter label="Restart" /></div>
    <div class="col-6"><counter label="Attack" /></div>
    <div class="col-6"><counter label="Special Attack" /></div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import counter from ".//components/counter.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    counter,
  },
  data: function () {
    return {};
  },

  methods: {
    sum(CsButtonValue) {
      this.total += CsButtonValue;
    },
  },
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
