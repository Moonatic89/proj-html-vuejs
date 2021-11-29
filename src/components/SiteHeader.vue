<template>
  <header>
    <nav>
      <div class="logo">
        <img src="../assets/img/logo-sidearea-1.png" alt="" />
      </div>
      <div class="navbar">
        <ul>
          <li>
            HOME
            <div class="navOverlay"></div>
          </li>
          <li>
            PAGES
            <div class="navOverlay"></div>
          </li>
          <li>
            PORTFOLIO
            <div class="navOverlay"></div>
          </li>
          <li>
            BLOG
            <div class="navOverlay"></div>
          </li>
          <li>
            SHOP
            <div class="navOverlay"></div>
          </li>
          <li>
            ELEMENTS
            <div class="navOverlay"></div>
          </li>
          <li class="img">
            <img src="../assets/img/svg-1.svg" alt="" />
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../assets/scss/colors.scss";

header {
  height: 90px;

  nav {
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-family: "Muli", sans-serif;

    .logo {
      padding: 1rem;

      img {
        height: 100%;
      }
    }

    ul {
      display: flex;
      font-weight: bold;
      list-style: none;

      li img {
        transform: translate(0, -12.5%);
      }

      li {
        padding: 0.5rem 1.5rem;
      }

      li:hover .navOverlay {
        display: block;
      }

      .navOverlay {
        display: none;
        border-radius: 2px;
        position: relative;
        z-index: -1;
        transform: translate(-10%, -75%);
        width: 120%;
        height: 50%;
        background-color: $headerBorder;
      }
    }
  }
}
</style>
