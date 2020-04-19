<template>
  <div id="app">
    <pokemon/>
  </div>
</template>

<script>
import Pokemon from "./components/Pokemon.vue";

export default {
  name: "app",
  components: {
    Pokemon
  }
};
</script>

<style>
#app {
  background: #07A8EC;
}

body {
  margin: 0;
  padding: 0;
}

</style>
