<template>
  <div id="app">
    <on-off-counter></on-off-counter>
    <hr />
  </div>
</template>

<script>

import OnOffCounter from './components/OnOffCounter.vue';

export default {
  name: "App",
  components: {
    OnOffCounter,
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
