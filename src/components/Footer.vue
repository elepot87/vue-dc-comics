<template>
  <footer class="footer">
    <div class="footerone">
      <nav class="nav-footer">
        <!-- Colonna sx -->
        <div class="col-sx">
          <h4>DC COMICS</h4>
          <ul class="footer-col sx">
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
          </ul>
          <h4>SHOP</h4>
          <ul class="footer-col sx">
            <li>ciao</li>
            <li>ciao</li>
          </ul>
        </div>
        <!-- Colonna centrale -->
        <div class="col-center">
          <h4>DC</h4>
          <ul class="footer-col center">
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
          </ul>
        </div>
        <!-- Colonna dx -->
        <div class="col-dx">
          <h4>SITES</h4>
          <ul class="footer-col dx">
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
          </ul>
        </div>
      </nav>
    </div>
    <div class="footer-social">
      <div class="container-footer-social">social</div>
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

.col-sx,
.col-center,
.col-dx {
  width: calc(100% / 5);
}

.footer-col {
  list-style: none;
  padding: 0;
}

.footer-logo {
  width: 50%;
}

.footer-social {
  background-color: #303030;
}

.container-footer-social {
  max-width: 1170px;
  margin: 0 auto;
  padding: 20px 0;
}
</style>
