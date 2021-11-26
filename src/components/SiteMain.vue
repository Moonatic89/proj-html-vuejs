<template>
  <main>
    <Jumbo />
    <Selector />
  </main>
</template>

<script>
import Jumbo from "../components/Jumbo.vue";
import Selector from "../components/Selector.vue";

export default {
  components: {
    Jumbo,
    Selector,
  },
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../assets/scss/colors.scss";
</style>
