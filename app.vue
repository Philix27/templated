<template>
  <div>
    <p>Yes man</p>
    <p>Hello Nuxt</p>
  </div>
  <Nav />

</template>

<script>
import Nav from "./src/comps/nav.vue";

export default {
  name: "app",
  components: { Nav },

  data() {
    return {
      name: "Templated",
    };
  },
};
</script>

