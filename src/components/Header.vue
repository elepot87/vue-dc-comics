<template>
  <header>
    <div class="container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo DC" />
      </a>
      <nav class="nav-menu">
        <ul class="main-menu">
          <li><a href="/"></a>Characters</li>
          <li><a href="#"></a>Comics</li>
          <li><a href="#"></a>Movies</li>
          <li><a href="#"></a>Tv</li>
          <li><a href="#"></a>Games</li>
          <li><a href="#"></a>Collectibles</li>
          <li><a href="#"></a>Videos</li>
          <li><a href="#"></a>Fans</li>
          <li><a href="#"></a>News</li>
          <li><a href="#"></a>Shop</li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
.container {
  max-width: 1170px;
  margin: 0 auto;
  padding: 10px;
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
