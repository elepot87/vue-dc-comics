<template>
  <div id="app">
    <Header />
    <Products />
    <Features />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Products from "@/components/Products.vue";
import Features from "@/components/Features.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Products,
    Features,
    Footer,
  },
};
</script>

<style lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";
</style>
