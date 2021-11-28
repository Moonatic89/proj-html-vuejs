<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="logo">
          <img src="../assets/img/logo-sidearea-1.png" alt="" />
          <div>Let's Get Creative</div>
        </div>

        <div class="email">
          <div>maree.qode@gmail.com</div>
          <div>+44645 321 789</div>
        </div>

        <div class="address">
          <div>Avenue d'Auderghem 10</div>

          <div>1040 Brussels, Belgium</div>
        </div>

        <div class="social">
          <div>Stay in touch with us</div>
          <div class="icons">
            <i class="fab fa-twitter"></i>
            <i class="fab fa-pinterest"></i>
            <i class="fab fa-facebook"></i>
            <i class="fab fa-linkedin"></i>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../assets/scss/colors.scss";
footer {
  width: 100%;
  height: 228px;
  background-color: $backgroundScrollUp;

  .container {
    width: 50%;
    height: 100%;
    margin: auto;
    .row {
      height: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;

      div {
        margin: 1rem 0;
      }

      .icons {
        display: flex;
        justify-content: space-between;
      }
    }
  }
}
</style>
