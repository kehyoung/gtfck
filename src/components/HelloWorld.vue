<template>
  <div class="map"></div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
html,
body {
  height: 100%;
  margin: 0;
}

#map {
  min-height: 100%;
}
</style>
