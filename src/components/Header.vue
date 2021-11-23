<template>
  <header>
    <div class="container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo DC" />
      </a>
      <nav class="nav-menu">
        <ul class="main-menu">
          <li v-for="(link, index) in navLinks" :key="`link-${index}`">
            <a :href="link.url">{{ link.text }}</a>
          </li>
          <!-- <li><a href="/comics"></a>Comics</li>
          <li><a href="/movies"></a>Movies</li>
          <li><a href="/tv"></a>Tv</li>
          <li><a href="/games"></a>Games</li>
          <li><a href="/collectibles"></a>Collectibles</li>
          <li><a href="/videos"></a>Videos</li>
          <li><a href="/fans"></a>Fans</li>
          <li><a href="/news"></a>News</li>
          <li><a href="/shop"></a>Shop</li> -->
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
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.main-menu {
  list-style: none;
  display: flex;
  li {
    margin: 0 10px;
  }
}
</style>
