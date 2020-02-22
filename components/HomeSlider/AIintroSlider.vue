<template>
  <div class="slide">
    <div class="welcome_message">
      <h2>
        Your technology partner for<br>
        <span>Product Development</span> and
        <span>Digital  <br>Transformation</span>
      </h2>
      <p class="sub_title">
        Huduma Plus is trusted by big and small enterprises, and amazing startups around the
        Nation to accelerate their business with cutting-edge technology and solutions.
      </p>
      <a-button class="huduma-red-button"> LETS TALK
        <a-icon type="phone"/>
      </a-button>
    </div>
    <div class="slide_anim">
      <div class="triangle_wrap triangle_black">
        <div class="triangle">
          <div class="triangle_inner"></div>
        </div>
      </div>
      <div class="equation_behind"></div>
      <div class="equation2_behind"></div>
      <div class="equation_front"></div>
      <div class="slide_img"></div>
      <div class="triangle" id="triangle1">
        <div class="triangle_inner"></div>
      </div>
      <div class="triangle" id="triangle2">
        <div class="triangle_inner"></div>
      </div>
      <div class="triangle" id="triangle3">
        <div class="triangle_inner"></div>
      </div>
      <div class="triangle" id="triangle4">
        <div class="triangle_inner"></div>
      </div>
      <div class="triangle" id="triangle5">
        <div class="triangle_inner"></div>
      </div>
      <div class="triangle" id="triangle6">
        <div class="triangle_inner"></div>
      </div>
      <div class="anim_line" id="line1"></div>
      <div class="anim_line" id="line2"></div>
      <div class="anim_line" id="line3"></div>
      <div class="anim_line" id="line4"></div>
    </div>
  </div>
</template>

<script>
    export default {}
</script>

<style scoped>
  @import '../../assets/css/anim.css';
  .slide {
    color: #585858;
    background-image: url(https://res.cloudinary.com/intelecs/image/upload/v1582373878/huduma/Home_page_image....png);
    background-size: cover;
    height: 100vh;
    width: 100%;
    left: 100%;
    font-family: montserrat_bold, sans-serif;
    overflow: hidden;
  }

  .welcome_message {
    margin: 16% 30px 40px 50px;
    position: relative;
    z-index: 1;
    float: left;

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

  .sub_title, .welcome_message {
    text-align: left;
    font-family: "Lato Light"
  }

  .welcome_message > .sub_title {
    color: #c7c7c7;
    font-size: 14px;
    margin: 0 0 30px 0;
    font-family: "Lato Light";
    line-height: 1.4;
    text-align: left;
  }

  .welcome_message > h2 {
    color: #ffffff;
    font-size: 36px;
    line-height: 1.3;
    font-family: "Lato Light"
  }
  .welcome_message > h2 > span {
    font-style: normal;
    font-weight: bolder;
  }
</style>
