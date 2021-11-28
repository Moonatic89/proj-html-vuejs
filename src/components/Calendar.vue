<template>
  <div id="Calendar">
    <div class="container">
      <div class="row">
        <div class="col_4">
          <div class="tag">
            <div class="day">07</div>
            <div class="date">
              <!-- <img src="../assets/img/calendar-piece.png" alt="" /> -->
              <span>MAY '19</span>
            </div>
          </div>
          <div class="image">
            <img src="../assets/img/h-2-blog-img-1.jpg" alt="" />
          </div>

          <div class="title">
            This way, loves: a detailed guide through new design
          </div>
          <div class="owner">By Emily Fields</div>
        </div>

        <div class="col_4">
          <div class="tag">
            <div class="day">07</div>
            <div class="date">
              <!-- <img src="../assets/img/calendar-piece.png" alt="" /> -->
              <span>MAY '19</span>
            </div>
          </div>
          <div class="image">
            <img src="../assets/img/h-2-blog-img-2.jpg" alt="" />
          </div>

          <div class="title">
            I try to give people a different way of looking art
          </div>
          <div class="owner">By Emily Fields</div>
        </div>

        <div class="col_4">
          <div class="tag">
            <div class="day">07</div>
            <div class="date">
              <!-- <img src="../assets/img/calendar-piece.png" alt="" /> -->
              <span>MAY '19</span>
            </div>
          </div>
          <div class="image">
            <img src="../assets/img/h-2-blog-img-3.jpg" alt="" />
          </div>

          <div class="title">
            Introduce Richard Laparrière of those amazing features
          </div>
          <div class="owner">By Emily Fields</div>
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
#Calendar {
  .row {
    display: flex;
    justify-content: center;

    .col_4 {
      width: calc(100% / 4);
      padding: 4rem;

      .tag {
        position: relative;
        top: 3.5rem;
        left: 1rem;
        .day {
          width: 65px;
          height: 35px;
          background-color: $backgroundScrollUp;
          line-height: 35px;
          text-align: center;
          font-size: 2rem;
          font-style: italic;
          font-weight: bold;
        }

        .date {
          width: 65px;
          height: 35px;
          background-image: url("../assets/img/calendar-piece.png");
          line-height: 25px;
          text-align: center;
          span {
            font-size: 0.8rem;
            // background-color: yellow;
          }
        }
      }

      .title {
        font-size: 2rem;
        margin-top: 1rem;
      }

      .owner {
        margin-top: 1rem;
        font-style: italic;
      }

      .image {
        img {
          width: 100%;
        }
      }
    }
  }
}
</style>