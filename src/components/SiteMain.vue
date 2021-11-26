<template>
  <main>
    <Jumbo />
    <Selector />
    <Workflow />
    <ContactUs />
    <Calendar />
  </main>
</template>

<script>
import Jumbo from "../components/Jumbo.vue";
import Selector from "../components/Selector.vue";
import Workflow from "../components/Workflow.vue";
import ContactUs from "../components/ContactUs.vue";
import Calendar from "../components/Calendar.vue";

export default {
  components: {
    Jumbo,
    Selector,
    Workflow,
    ContactUs,
    Calendar,
  },
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../assets/scss/colors.scss";
</style>
