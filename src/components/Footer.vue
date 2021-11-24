<template>
  <footer class="footer">
    <div class="footerone container py-40">
      <nav class="nav-footer flex">
        <!-- Colonna sx -->
        <div class="col-sx">
          <h4 class="my-15">DC COMICS</h4>
          <ul class="footer-col sx p-0 no-list-style">
            <li
              v-for="(link, index) in linksDcComics"
              :key="link - footer - `${index}`"
            >
              <a :href="link.url">{{ link.text }}</a>
            </li>
          </ul>
          <h4 class="mt-20 mb-15">SHOP</h4>
          <ul class="footer-col sx p-0 no-list-style">
            <li
              v-for="(link, index) in shopDC"
              :key="link - footer - shop - `${index}`"
            >
              <a :href="link.url">{{ link.text }}</a>
            </li>
          </ul>
        </div>
        <!-- Colonna centrale -->
        <div class="col-center">
          <h4 class="my-15">DC</h4>
          <ul class="footer-col center p-0 no-list-style">
            <li
              v-for="(link, index) in linkDC"
              :key="linkDC - footer - `${index}`"
            >
              <a :href="link.url">{{ link.text }}</a>
            </li>
          </ul>
        </div>
        <!-- Colonna dx -->
        <div class="col-dx">
          <h4 class="my-15">SITES</h4>
          <ul class="footer-col dx p-0 no-list-style">
            <li
              v-for="(link, index) in sitesDC"
              :key="sitesDC - footer - `${index}`"
            >
              <a :href="link.url">{{ link.text }}</a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <div class="footer-social">
      <div class="container py-20 flex flex-center">
        <!-- Col left -->
        <div>
          <button class="footer-cta">SIGN-UP NOW</button>
        </div>
        <!-- Col right -->
        <div class="flex flex-center">
          <span class="follow">FOLLOW US</span>
          <img src="../assets/img/footer-facebook.png" alt="icona facebook" />
          <img src="../assets/img/footer-twitter.png" alt="icona twitter" />
          <img src="../assets/img/footer-youtube.png" alt="icona-youtube" />
          <img src="../assets/img/footer-pinterest.png" alt="icona pinterest" />
          <img src="../assets/img/footer-periscope.png" alt="icona periscope" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      linksDcComics: [
        {
          text: "Characters",
          url: "/characters",
          current: true,
        },
        {
          text: "Comics",
          url: "/comics",
          current: false,
        },
        {
          text: "Movies",
          url: "/movies",
          current: false,
        },
        {
          text: "Tv",
          url: "/tv",
          current: false,
        },
        {
          text: "Games",
          url: "/games",
          current: false,
        },
        {
          text: "Videos",
          url: "/videos",
          current: false,
        },
        {
          text: "News",
          url: "/news",
          current: false,
        },
      ],
      shopDC: [
        {
          text: "Shop DC",
          url: "/shop",
          current: false,
        },
        {
          text: "Shop DC Collectibles",
          url: "/collectibles",
          current: false,
        },
      ],
      linkDC: [
        {
          text: "Terms of Use",
          url: "/terms-use",
          current: false,
        },
        {
          text: "Privacy policy",
          url: "/privacy-policy",
          current: false,
        },
        {
          text: "AD Choices",
          url: "/ad-choices",
          current: false,
        },
        {
          text: "Advertising",
          url: "/advertising",
          current: false,
        },
        {
          text: "Jobs",
          url: "/jobs",
          current: false,
        },
        {
          text: "Subscriptions",
          url: "/subscriptions",
          current: false,
        },
        {
          text: "Talent Workshop",
          url: "/talent-workshop",
          current: false,
        },
        {
          text: "CPSC Workshops",
          url: "/cpsc-workshops",
          current: false,
        },
        {
          text: "Ratings",
          url: "/ratings",
          current: false,
        },
        {
          text: "Shop help",
          url: "/shop-help",
          current: false,
        },
        {
          text: "Contact us",
          url: "/contact-us",
          current: false,
        },
      ],
      sitesDC: [
        {
          text: "DC",
          url: "/dc",
          current: false,
        },
        {
          text: "MAD Magazine",
          url: "/mad-magazine",
          current: false,
        },
        {
          text: "DC Kids",
          url: "/dc-kids",
          current: false,
        },
        {
          text: "DC Universe",
          url: "/dc-universe",
          current: false,
        },
        {
          text: "DC Power Visa",
          url: "/dc-power-visa",
          current: false,
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
@import "@/styles/footer";
</style>
