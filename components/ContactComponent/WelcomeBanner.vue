<template>
  <div class="contact_header">
    <!--<div class="slide_anim particle_wrap">
        <div class="anim_line" id="line1"></div>
        <div class="anim_line" id="line2"></div>
        <div class="anim_line" id="line3"></div>
        <div class="anim_line" id="line4"></div>
    </div> -->
    <a-row>
      <a-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12">
        <div class="cMap">
          <img src="https://accubits.com/wp-content/themes/accubits/images/contact/map.png.pagespeed.ce.eOTnr8hLEd.png">
        </div>
      </a-col>
      <a-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12">
        <div class="welcome_message">
          <h2>We are always ready <span>to respond to your needs</span></h2>
          <p>We would love to solve your pain points and challenges with technology innovation. Give us a hint about your
            challenge and we will get in touch with you shortly with an answer.<br>
          </p>
          <p style="color: black;">
            <strong>P: +255 757 123 008 (TZ)</strong>
            <strong><a href="" style="color: black;">E: contact@hudumaai.com</a></strong>
          </p>
          <div>
            <a-button class="huduma-red-button" style="margin: 8px;"> LETS TALK
              <a-icon type="phone"/>
            </a-button>
            <a-button class="huduma-outline-button" style="margin: 8px;"> REACH US
              <a-icon type="form"/>
            </a-button>
          </div>
        </div>
      </a-col>
    </a-row>
  </div>
</template>

<script>
    export default {
        name: "WelcomeBanner"
    }
</script>

<style scoped>
  img {
    height: auto;
    max-width: 100%;
    vertical-align: middle;
    border: 0;
  }

  .contact_header p {
    color: #c7c7c7;
    font-size: 17px;
    margin: 0 0 30px 0;
    padding: 15px 200px 15px 0;
    position: relative;
    font-family: "Lato Light";
    line-height: 30px;
  }
  .contact_header {
    padding-top: 90px;
    padding-bottom: 90px;
    background: #f5f5f5 no-repeat center;
    background-size: cover;
    overflow: hidden;
    color: #fff;
    z-index: 1;
    height: 100%;
  }
  .welcome_message {
    position: absolute;
    right: 6%;
    top: 25%;
    margin: 0;
    max-width: 540px
  }
  .welcome_message h2 {
    font-size: 30px;
    line-height: 34px;
    text-shadow: none;
    color: #000;
    font-family: "Lato Light"
  }
  .welcome_message h2 span {
    font-family: "Lato Semibold";
    text-transform: uppercase;
    display: block
  }
  .welcome_message p {
    font-size: 14px;
    padding: 15px 20px 15px 0;
    position: relative;
    line-height: 1.4;
    font-family: "Lato Light";
    background: none;
    color: #888;
    margin: 0 0 25px 0;
  }
  .welcome_message p:before {
    display: none
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
  }

  .huduma-outline-button {
    background: transparent;
    box-shadow: none;
    height: 35px;
    color: #ef0d33;
    border-radius: 3px;
    border: 1px solid #ef0d33;
    cursor: pointer;
    font-size: small;
    outline: none;
  }

  .huduma-red-button:hover {
    background:transparent !important;
    box-shadow: none;
    height: 35px;
    color: #ef0d33;
    border-radius: 3px;
    border: 1px solid #ef0d33;
    cursor: pointer;
    font-size: small;
    outline: none;
  }

  .huduma-outline-button:hover {
    background: #ef0d33;
    border: none;
    box-shadow: none;
    height: 35px;
    color: #fff;
    border-radius: 3px;
    cursor: pointer;
    font-size: small;
    outline: none;
  }
</style>
