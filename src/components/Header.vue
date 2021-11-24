<template>
  <header>
    <div class="container flex flex-center">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo DC" />
      </a>
      <nav class="nav-menu">
        <ul class="main-menu flex no-list-style">
          <li v-for="(link, index) in navLinks" :key="`link-${index}`">
            <a :href="link.url">{{ link.text }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      navLinks: [
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
          text: "Collectibles",
          url: "/collectibles",
          current: false,
        },
        {
          text: "Videos",
          url: "/videos",
          current: false,
        },
        {
          text: "Fans",
          url: "/fans",
          current: false,
        },
        {
          text: "News",
          url: "/news",
          current: false,
        },
        {
          text: "Shop",
          url: "/shop",
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
@import "@/styles/header";
</style>
