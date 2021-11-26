<template>
  <div id="app">
    <div class="scrollUp">
      <div class="svg">
        <img src="./assets/img/svg-2.svg" alt="" />
      </div>
    </div>
    <SiteHeader />
    <SiteMain />
    <SiteFooter />
  </div>
</template>

<script>
//import HelloWorld from "./components/SiteFooter.vue";
import SiteFooter from "./components/SiteFooter.vue";
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/common.scss";
@import "./assets/scss/colors.scss";
#app {
  width: 2200px;
  position: relative;

  .scrollUp {
    position: fixed;
    transform: translate(-50%, -50%);
    right: 20px;
    bottom: 20px;
    width: 40px;
    height: 40px;
    line-height: 40px;
    font-size: 2rem;
    text-align: center;

    .svg {
      background-color: $backgroundScrollUp;
    }
  }
}
</style>

