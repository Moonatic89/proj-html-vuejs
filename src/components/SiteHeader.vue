<template>
  <header>
    <nav>
      <div class="logo">
        <img src="../assets/img/logo-sidearea-1.png" alt="" />
      </div>
      <div class="navbar">
        <ul>
          <li>HOME</li>
          <li>PAGES</li>
          <li>PORTFOLIO</li>
          <li>BLOG</li>
          <li>SHOP</li>
          <li>ELEMENTS</li>
          <li>img here</li>
        </ul>
      </div>
    </nav>

    <h1>SITE HEADER</h1>
  </header>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
header {
  height: 90px;
  background-color: wheat;

  nav {
    display: flex;
    justify-content: space-between;

    ul {
      display: flex;

      list-style: none;
    }
  }
}
</style>
