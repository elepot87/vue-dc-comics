<template>
  <div id="app">
    <Header />
    <Products />
    <Features />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Products from "@/components/Products.vue";
import Features from "@/components/Features.vue";

export default {
  name: "App",
  components: {
    Header,
    Products,
    Features,
  },
};
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Helvetica, Arial, sans-serif;
}

.container {
  max-width: 1170px;
  margin: 0 auto;
  padding: 10px;
}
</style>
