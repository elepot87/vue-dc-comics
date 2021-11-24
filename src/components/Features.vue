<template>
  <div class="features py-20">
    <div class="container">
      <ul class="list-features flex no-list-style">
        <li
          v-for="(feature, index) in features"
          :key="`feature-${index}`"
          class="flex"
        >
          <img :src="feature.imgFeatures" :alt="feature.text" />
          <span>{{ feature.text }}</span>
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
          imgFeatures: require("@/assets/img/buy-comics-digital-comics.png"),
          text: "Digital comics",
        },
        {
          imgFeatures: require("@/assets/img/buy-comics-merchandise.png"),
          text: "DC Merchandise",
        },
        {
          imgFeatures: require("@/assets/img/buy-comics-subscriptions.png"),
          text: "Subscription",
        },
        {
          imgFeatures: require("@/assets/img/buy-comics-shop-locator.png"),
          text: "Comic shop locator",
        },
        {
          imgFeatures: require("@/assets/img/buy-dc-power-visa.svg"),
          text: "DC Power Visa",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";
@import "@/styles/variables";

.features {
  background: $primary-color;
  // height: 150px;
}
.list-features {
  li {
    width: calc(100% / 5);
    color: $white;
    align-items: center;
    span {
      text-transform: uppercase;
      font-size: $font-menu;
    }
    img {
      margin-right: 15px;
      width: 20%;
    }
  }
}
</style>
