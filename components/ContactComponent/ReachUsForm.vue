<template>
  <section class="huduma-form footer_section">
    <div class="footer_head">
      <h2>Contact us</h2>
    </div>
    <!--<a-form>
      <a-row class="form-row" justify="space-between">
        <a-col
          class="forn_margin"
          :xs="10"
          :sm="10"
          :md="10"
          :lg="10"
          :xl="10" >
          <a-input class="huduma-input" placeholder="FULL NAME">
          </a-input>
        </a-col>
        <a-col
          class="forn_margin"
          :xs="10"
          :sm="10"
          :md="10"
          :lg="10"
          :xl="10">
          <div class="loc_img">
            <a-input class="huduma-input" placeholder="TITLE/OCCUPATION">
            </a-input>
          </div>
        </a-col>
      </a-row>
      <a-row class="form-row" justify="space-between">
        <a-col
          class="forn_margin"
          :xs="10"
          :sm="10"
          :md="10"
          :lg="10"
          :xl="10" >
          <a-input class="huduma-input" placeholder="COMPANY/ORGANIZATION">
          </a-input>
        </a-col>
        <a-col
          class="forn_margin"
          :xs="10"
          :sm="10"
          :md="10"
          :lg="10"
          :xl="10">
          <div class="loc_img">
            <a-input class="huduma-input" placeholder="EMAIL">
            </a-input>
          </div>
        </a-col>
      </a-row>
      <a-row class="form-row" justify="space-between">
        <a-col
          class="forn_margin"
          :xs="10"
          :sm="10"
          :md="10"
          :lg="10"
          :xl="10" >
          <a-input class="huduma-input" placeholder="PHONE">
          </a-input>
        </a-col>
      </a-row>
      <a-row class="form-row" justify="space-between">
        <a-col
          class="forn_margin"
          :span="20">
          <a-textarea class="huduma-input text-area" placeholder="PROJECT">
          </a-textarea>
        </a-col>
      </a-row>
      <a-row class="form-row" justify="space-between">
        <a-col
          class="forn_margin"
          :span="20">
          <a-button class="huduma-red-button" style="margin: 8px;"> SUBMIT
            <a-icon type="check-circle" />
          </a-button>
        </a-col>
      </a-row>
    </a-form> -->
  </section>
</template>

<script>
    export default {}
</script>

<style scoped>
  .huduma-form {
    margin-bottom: 40px;
  }
  .form-row {
    margin-top: 50px;
  }
  .forn_margin {
    margin-right: 20px;
  }
  .huduma-input {
    border-width: 0 0 1px 0;
    border-style: solid;
    color:  white;
    font-family: "Lato Medium";
    font-size: 15px;
    border-color: rgba(255, 255, 255, 0.2) !important;
    outline: none;
    border-radius: 0px;
    background: transparent;
    padding: 5px 5px;
    margin: 0;
    width: 100%;
    height: auto;
  }
  .huduma-input:hover{
    outline: none;
    box-shadow: none;
    border-color: rgba(255, 255, 255, 0.2) !important;
    border-right-width: 0 !important;
    border-style: solid;
  }
  .huduma-input:focus {
    outline: none;
    box-shadow: none;
    /*border-width: 0 0 2px 0;*/
    border-color: rgba(255, 255, 255, 0.2) !important;
    border-right-width: 0 !important;
  border-style: solid;
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

  @media only screen and (max-width: 595px) {
    .huduma-input {
      font-size: 13px;
    }
  }

  @media only screen and (max-width: 1300px) {
    .huduma-input {
      font-size: 13px;
    }
  }

  @media only screen and (max-width: 595px) {
    .huduma-input {
      font-size: 13px;
    }
  }

  @media only screen and (max-width: 768px) {
    .footer_head {
      max-width: 500px;
    }
  }

  .footer_head {
    width: 500px;
  }

  @media only screen and (max-height: 700px) {
    .footer_head h2 {
      font-size: 40px;
    }
  }

  @media only screen and (max-height: 700px) {
    .footer_head h2 {
      margin-bottom: 20px;
      margin-top: 60px;
    }
  }

  @media only screen and (max-width: 900px) {
    .footer_head h2 {
      font-size: 34px;
    }
  }
  .footer_head h2 {
    font-size: 45px;
    color: #fff;
    font-family: "Lato Heavy";
    line-height: 20px;
  }
  .footer_head p:before {
    content: '';
    position: absolute;
    border-bottom: 3px solid #ef0d33;
    width: 50px;
    left: 10px;
    top: 10px;
  }
  .footer_head p {
    color: #a4a4a4;
    padding-left: 80px;
    position: relative;
    margin: 0px;
  }
</style>
