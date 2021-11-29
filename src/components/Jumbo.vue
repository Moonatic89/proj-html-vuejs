<template>
  <div id="Jumbo">
    <div class="chevron left">
      <i class="fas fa-chevron-left"></i>
    </div>
    <div class="chevron right">
      <i class="fas fa-chevron-right"></i>
    </div>

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

    <div class="dots">
      <div class="dot"></div>
      <div class="dot"></div>
      <div class="dot big"></div>
    </div>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../assets/scss/colors.scss";

#Jumbo {
  height: 644px;
  width: 100%;
  position: relative;
  margin-bottom: 2rem;

  .chevron {
    position: absolute;
    width: 20px;
    height: 20px;
    line-height: 20px;
    text-align: center;
    background-color: $dotBorder;
    color: white;
    border-radius: 50%;
    top: 40%;
  }

  .left {
    left: 20px;
  }
  .right {
    right: 20px;
  }

  .container {
    height: 624px;
    display: flex;
    justify-content: center;
    align-items: center;

    .card {
      width: 600px;
      margin-right: 60px;
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

      .cardBtn:hover {
        background-color: $hoverContactButton;
        color: white;
      }
      .cardBtn {
        font-size: 0.8rem;
        background-color: white;
        border: 2px solid $dotBorder;
        width: 200px;
        height: 60px;
        line-height: 60px;
        text-align: center;
      }
    }

    .jumboImage {
      width: 900px;
      display: flex;
      // position: relative;

      .humans {
        align-self: center;
      }

      .leftArtifactColumn {
        height: 100%;

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
      .rightArtifactColumn {
        height: 100%;

        .artUpRg {
          top: -25px;
          right: 120px;
        }
        .artMidRg {
          top: 10px;
          left: -30px;
        }
        .artDwRg {
          top: 180px;
          left: 0;
        }
      }

      .humans {
        display: flex;
        justify-content: center;
      }
    }
  }

  .dots {
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;

    .dot {
      width: 9px;
      height: 9px;
      border-radius: 50%;
      background-color: $dotBorder;
      margin: 0 1rem;
    }

    .big {
      width: 13px;
      height: 13px;
    }
  }

  .pos_rel {
    position: relative;
  }
}
</style>
