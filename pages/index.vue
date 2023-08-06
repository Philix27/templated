<template>
  <div class="root">
    <Hero />
  </div>
</template>

<script>
import Hero from "./../src/comps/hero.vue";
export default {
  name: "app",
  components: { Hero },

  data() {
    return {
      name: "Templated",
    };
  },
};
</script>

<style scoped>
body {
  margin: 0px;
  padding: 0px;
}
.root {
  background-color: pink;
  height: 100vh;
}
</style>
