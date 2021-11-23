<template>
  <div class="products">
    <div class="container">
      <h1>-->Content goes here</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Product.vue",
};
</script>

<style scoped lang="scss">
.products {
  background: #000;
  height: 100px;
  .container {
    display: flex;
    align-items: center;
    height: 100%;
    padding: 0;
  }
}

h1 {
  color: white;
  font-size: 30px;
}
</style>
