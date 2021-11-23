<template>
  <footer class="footer">
    <div>
      <div class="footerone">
        <nav class="nav-footer">
          <!-- Colonna sx -->
          <!-- Colonna centrale -->
          <!-- Colonna dx -->
        </nav>
      </div>
      <div class="footer-social">social</div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
.footer {
  background-image: url("../assets/img/footer-bg.jpg");
  background-position: center top;
  background-repeat: no-repeat;
  background-size: cover;
  > div {
    max-width: 1170px;
    margin: 0 auto;
  }
}

.footerone {
  background-image: url("../assets/img/dc-logo-bg.png");
  background-position: right center;
  background-repeat: no-repeat;
  margin: 0 auto;
  padding: 40px 0;
  width: 1170px;
}

.nav-footer {
  width: 50%;
  display: flex;
}

.footer-logo {
  width: 50%;
}

.footer-social {
  background-color: #303030;
  margin-bottom: 0 auto;
  padding: 20px 0;
}
</style>
