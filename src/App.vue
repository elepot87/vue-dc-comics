<template>
  <div id="app">
    <Header />
    <Hero />
    <Products />
    <Features />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import Products from "@/components/Products.vue";
import Features from "@/components/Features.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Hero,
    Products,
    Features,
    Footer,
  },
};
</script>

<style lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";
@import "@/styles/variables";
</style>
