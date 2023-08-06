<template>
  <div class="container">
    <h1>Logo</h1>
    <ul class="nav_items">
      <li>Home</li>
      <li>Web</li>
      <li>Mobile</li>
      <li>Invoice</li>
      <li>Images</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {
      app: "Templated",
    };
  },
};
</script>

<style scoped>
.container {
  background-color: green;
  width: 100%;
  display: flex;
  color: #fff;
  padding: 0 20px;
  height: 50px;
  line-height: 50px;
  justify-content: space-between;
  align-items: center;
  ul {
    display: flex;
    li {
      text-decoration: none;
      padding: 0 10px;
    }
  }
}
</style>
