<template>
  <div class="features">
    <div class="container">
      <ul class="list-features flex">
        <li v-for="(feature, index) in features" :key="`feature-${index}`">
          <img :src="feature.imgFeatures" :alt="feature.text" />
          <span></span>
        </li>
      </ul>
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
          imgFeatures: require('@/assets/img/buy-comics-digital-comics.png'),
          text: "Digital comics",
        },
        {
          imgFeatures: require('@/assets/img/buy-comics-merchandise.png'),
          text: "DC Merchandise",
        },
        {
          imgFeatures: require('@/assets/img/buy-comics-subscriptions.png'),
          text: "Subscription",
        },
        {
          imgFeatures: require('@/assets/img/buy-comics-shop-locator.png'),
          text: "Comic shop locator",
        },
        {
          imgFeatures: require('@/assets/img/buy-dc-power-visa.svg'),
          text: "DC Power Visa",
        },
      ],
    },
  },
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
