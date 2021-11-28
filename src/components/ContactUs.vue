<template>
  <div id="ContactUs">
    <div class="textBox">
      <div class="title">
        Want to work with us? Send us <span>a message!</span>
      </div>
      <div class="text">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio
        consectetur dignissimos molestiae magnam exercitationem amet odit
        aliquam aliquid debitis maxime? Lorem ipsum dolor sit amet consectetur
        adipisicing elit. Odio numquam soluta rem est unde voluptatem nostrum a
        repellat similique beatae.
      </div>
      <div class="btn">CONTACT</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/colors.scss";

#ContactUs {
  width: 100%;
  height: 530px;
  background-color: $contactUsBackground;
  .textBox {
    display: flex;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    .title {
      font-size: 4rem;

      span {
        font-style: italic;
        font-weight: bold;
      }
    }
    .text {
      color: gray;
      margin: 2rem;
      text-align: center;
      width: 80%;
    }

    .btn {
      width: 224px;
      padding: 1.7rem 0;
      text-align: center;
      background-color: $contactButton;
    }
  }
}
</style>