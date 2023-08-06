<template>
  <Nav />
  <slot />
  <Footer />
</template>

<script>
import Nav from "../src/comps/nav";
import Footer from "../src/comps/footer.vue";

export default {
  name: "DefaultLayout",
  components: { Nav, Footer },
};
</script>

<style scoped></style>
