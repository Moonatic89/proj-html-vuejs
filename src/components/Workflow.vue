<template>
  <div id="Workflow">
    <div class="wipText">
      <div class="title">Working <span>process</span></div>
    </div>

    <div class="art">
      <div class="image">
        <img src="../assets/img/svg-3.svg" alt="" />
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col_3">
          <div class="iconBox">
            <div class="icon">
              <i class="fas fa-lightbulb greenish"></i>
            </div>

            <div class="iconTitle">First theres an idea</div>

            <div class="iconSubText">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              natus ducimus adipisci? Vero, amet consequuntur!
            </div>
          </div>
        </div>
        <div class="col_3">
          <div class="iconBox">
            <div class="icon">
              <i class="far fa-comment yellowish"></i>
            </div>

            <div class="iconTitle">Then we talk about it</div>

            <div class="iconSubText">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              natus ducimus adipisci? Vero, amet consequuntur!
            </div>
          </div>
        </div>
        <div class="col_3">
          <div class="iconBox">
            <div class="icon">
              <i class="fas fa-cloud bordeaux"></i>
            </div>

            <div class="iconTitle">And we think aout it</div>

            <div class="iconSubText">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              natus ducimus adipisci? Vero, amet consequuntur!
            </div>
          </div>
        </div>
        <div class="col_3">
          <div class="iconBox">
            <div class="icon">
              <i class="fas fa-pencil-alt orangeish"></i>
            </div>

            <div class="iconTitle">So we draw along</div>

            <div class="iconSubText">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              natus ducimus adipisci? Vero, amet consequuntur!
            </div>
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
  margin-bottom: 5rem;
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

  .art {
    width: 50%;
    margin: auto;
    position: relative;

    .image {
      position: absolute;
      top: 0;
      left: 0;
      z-index: -1;

      img {
        width: 100%;
      }
    }
  }

  .row {
    display: flex;
    margin: auto;
    width: 60%;
    justify-content: space-between;

    .col_3 {
      width: calc(100% / 4);

      .iconBox {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;

        .icon > i {
          vertical-align: middle;
          font-size: 3.5rem;
        }

        .icon {
          background-color: $workingBacgkround;
          width: 162px;
          height: 162px;
          line-height: 162px;
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
        }

        .iconText {
          width: 50%;
        }
        .iconTitle {
          margin: 1rem 0;
          font-size: 1.5rem;
          font-weight: bold;
        }
        .iconSubText {
          width: 80%;
          color: gray;
          font-size: 0.8rem;
        }
      }
    }
  }
}
</style>