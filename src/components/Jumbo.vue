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
        <div class="leftArtifactColumn">
          <div class="artUpLf pos_rel">
            <img src="../assets/img/short-slider-rev-1-img-2.png" alt="" />
          </div>
          <div class="artMidLf pos_rel">
            <img src="../assets/img/h-2-slider-img-12.png" alt="" />
          </div>
          <div class="artDwLf pos_rel">
            <img src="../assets/img/h-2-slider-img-13.png" alt="" />
          </div>
        </div>
        <div class="humans">
          <div class="girl">
            <img src="../assets/img/h-2-slider-img-15.png" alt="" />
          </div>
          <div class="boy">
            <img src="../assets/img/h-2-slider-img-16.png" alt="" />
          </div>
        </div>
        <div class="rightArtifactColumn">
          <div class="artUpRg pos_rel">
            <img src="../assets/img/h-2-slider-img-14.png" alt="" />
          </div>
          <div class="artMidRg pos_rel">
            <img src="../assets/img/short-slider-rev-1-img-6.png" alt="" />
          </div>
          <div class="artDwRg pos_rel">
            <img src="../assets/img/h-2-slider-img-17.png" alt="" />
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
      display: flex;
      // position: relative;

      .humans {
        align-self: center;
      }

      .leftArtifactColumn {
        height: 100%;
        background-color: chocolate;

        .artUpLf {
          top: -25px;
          left: 50px;
        }
        .artMidLf {
          top: 100px;
          left: -30px;
        }
        .artDwLf {
          top: 230px;
          left: 20px;
        }
      }
      .humans {
        display: flex;
        justify-content: center;
      }
    }
  }

  .pos_rel {
    position: relative;
  }
}
</style>
