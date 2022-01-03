<template>
  <div id="app">
    <Map />
  </div>
</template>

<script>
import Map from "./components/AnimatedMarkerMap";

export default {
  name: "App",
  components: {
    Map,
  },
};
</script>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
}
</style>