<template>
  <div>
    <button @click="upFunction" class="btn btn-warning">{{label}}</button>
    <p v-bind:style="{fontSize: fsize + 'px'}">{{counter}}</p>
  </div>
</template>
<script>
export default {
  data: function () {
    return {

      ClassObject: {

      }
    };
  },
  props: {
    label: String,
  },
  medthod: {
    randomDamageSpi: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageIron: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageHulk: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageAkin: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageDo: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageCell: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageThanos: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    randomDamageVader: function (min, max) {
      return Math.max(Math.floor(Math.random() * max) + 1, min);
    },
    

  },
};
</script>
<style>
</style>