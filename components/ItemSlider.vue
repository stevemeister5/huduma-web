<template>
    <a-carousel horizontal autoplay>
      <a-iintro-slider />
    </a-carousel>
</template>

<script>
  import AIintroSlider from "./HomeSlider/AIintroSlider"

    export default {
        name: 'ItemSlider',
        components: {
            AIintroSlider
        }
    }
</script>

<style scoped>
  /* For demo */
  .ant-carousel >>> .slick-slide {
    text-align: center;
    height: 100%;
    margin-top: 10px;
    overflow: hidden;
  }
  .huduma-red-button {
    background: #ef0d33 !important;
    border: none;
    box-shadow: none;
    height: 35px;
    color: #fff;
    border-radius: 3px;
    cursor: pointer;
    font-size: small;
    outline: none;
    background-position: right;
    background-repeat: no-repeat;
  }
</style>
