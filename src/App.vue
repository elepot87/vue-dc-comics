<template>
  <div id="app">
    <Header />
    <Products />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Products from "@/components/Products.vue";

export default {
  name: "App",
  components: {
    Header,
    Products,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Helvetica, Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1170px;
  margin: 0 auto;
  padding: 10px;
}
</style>
