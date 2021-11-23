<template>
  <div class="products">
    <div class="container flex flex-center">
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
@import "@/styles/globals";
@import "@/styles/utilities";
@import "@/styles/variables";

.products {
  background: $third-color;
  height: 100px;
  .container {
    height: 100%;
    padding: 0;
  }
}

h1 {
  color: $white;
  font-size: 30px;
}
</style>
