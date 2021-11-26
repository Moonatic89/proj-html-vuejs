<template>
  <div id="Workflow">
    <div class="wipText">
      <div class="title">Working <span>process</span></div>
    </div>

    <div class="art"><img src="" alt="" /></div>

    <div class="container">
      <div class="row">
        <div class="col_3">
          <div class="iconBox">
            <i class="fas fa-lightbulb greenish"></i>
          </div>
        </div>
        <div class="col_3">
          <div class="iconBox">
            <i class="far fa-comment yellowish"></i>
          </div>
        </div>
        <div class="col_3">
          <div class="iconBox">
            <i class="fas fa-cloud bordeaux"></i>
          </div>
        </div>
        <div class="col_3">
          <div class="iconBox">
            <i class="fas fa-pencil-alt orangeish"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/colors.scss";

#Workflow {
  .wipText {
    width: 100%;
    text-align: center;
    padding: 3rem;
    .title {
      font-size: 4rem;

      span {
        font-style: italic;
        font-weight: bold;
      }
    }
  }

  .row {
    display: flex;
    margin: auto;
    width: 55%;
    justify-content: space-between;

    .iconBox {
      background-color: $workingBacgkround;
      width: 162px;
      height: 162px;
      line-height: 162px;
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 50%;

      .greenish {
        color: $iconGreen;
      }
      .yellowish {
        color: $iconYellow;
      }
      .bordeaux {
        color: $iconBordeaux;
      }
      .orangeish {
        color: $iconOrange;
      }

      i {
        font-size: 3.5rem;
      }
    }
  }
}
</style>