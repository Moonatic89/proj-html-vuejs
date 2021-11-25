<template>
  <div id="Jumbo">
    <div class="container">
      <div class="card">
        <div class="cardTitle">Devotion that never <span>ends</span></div>
        <div class="cardSubtitle">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Id, quaerat?
          Officia quaerat expedita voluptate aut? Enim sequi pariatur assumenda
          in.
        </div>
        <div class="cardBtn">READ MORE</div>
      </div>
      <div class="jumboImage">
        <div class="humans">
          <div class="girl">
            <img src="../assets/img/h-2-slider-img-15.png" alt="" />
          </div>
          <div class="boy">
            <img src="../assets/img/h-2-slider-img-16.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
#Jumbo {
  height: 644px;
  width: 100%;

  .container {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

    .card {
      width: 600px;
      // align-self: center;
      .cardTitle {
        font-size: 5rem;
        line-height: 70px;

        span {
          font-style: italic;
          font-weight: bold;
        }
      }
      .cardSubtitle {
        padding: 2rem 0;
        line-height: 25px;

        color: gray;
      }
      .cardBtn {
        font-size: 0.8rem;
        background-color: white;
        border: 2px solid red;
        width: 200px;
        height: 60px;
        line-height: 60px;
        text-align: center;
      }
    }

    .jumboImage {
      width: 900px;
      background-color: turquoise;
      position: relative;

      .humans {
        display: flex;
        justify-content: center;
      }
    }
  }
}
</style>
