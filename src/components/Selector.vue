<template>
  <div id="Selector" class="container">
    <div class="row">
      <div class="col_4">
        <img src="../assets/img/h-2-port-img-1.jpg" alt="" />
      </div>
      <div class="col_4">
        <img src="../assets/img/h-2-port-img-2.jpg" alt="" />
      </div>
      <div class="col_4">
        <img src="../assets/img/h-2-port-img-3.jpg" alt="" />
      </div>
      <div class="col_4">
        <img src="../assets/img/h-2-port-img-4.jpg" alt="" />
      </div>
      <div class="col_4">
        <img src="../assets/img/h-2-port-img-5.jpg" alt="" />
      </div>
      <div class="col_4">
        <img src="../assets/img/h-2-port-img-6.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
#Selector {
  .row {
    display: flex;
    flex-wrap: wrap;

    .col_4 {
      width: calc(100% / 3);
      height: calc(100% / 2);

      img {
        width: 100%;
        height: 100%;
      }
    }
  }
}
</style>