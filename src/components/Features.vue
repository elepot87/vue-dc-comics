<template>
  <div class="features">
    <div class="container">
      <h1>banda azzurra con features</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
  data() {
    return {
      features: [
        {
          imgFeatures: '../assets/img/buy-comics-digital-comics.png',
          text: "Digital comics",
        },
        {
          imgFeatures: '../assets/img/buy-comics-merchandise.png',
          text: "DC Merchandise",
        },
        {
          imgFeatures: '../assets/img/buy-comics-subscriptions.png',
          text: "Subscription",
        },
        {
          imgFeatures: '../assets/img/buy-comics-shop-locator.png',
          text: "Comic shop locator",
        },
        {
          imgFeatures: '../assets/img/buy-dc-power-visa.svg',
          text: "DC Power Visa",
        },

      ],
    },
  }
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";
@import "@/styles/variables";

.features {
  background: $primary-color;
  height: 150px;
}
</style>
