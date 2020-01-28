<template>
  <div class="section industries_section">
    <a-tabs class="huduma-tabs" defaultActiveKey="1" :size="large" style="margin-bottom: 16px; padding-left: 20px">
      <a-tab-pane  key="1">
      <span slot="tab">
        <img :src="require('@/assets/images/flags/tanzania.svg')">
        Tanzania
      </span>
        <h2>Here is our office</h2>
        <a-row>
          <a-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12">
            <location-card/>
          </a-col>
          <a-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12">
            <div class="loc_img">
              <img :src="require('@/assets/images/office/silicondar.jpg')">
            </div>
          </a-col>
        </a-row>
      </a-tab-pane>
    </a-tabs>
  </div>
</template>

<script>
  import LocationCard from './LocationCard'

    export default {
        name: "CountryTab",
        components: {
            LocationCard
        }
    }
</script>

<style scoped>
  .huduma-tabs img {
    height: 24px;
    margin: 8px;
  }
  .huduma-tabs span {
    color: #000;
    font-family: "Lato Heavy";
    text-transform: uppercase;
    font-size: 16px;
    font-weight: 500;
  }
  .ant-tabs-nav .ant-tabs-tab-active {
    color: #ef0d33 !important;
    font-weight: 500;
  }
  .loc_img {
    position: relative;
  }

  .loc_img img {
    height: auto;
    max-width: 100%;
    vertical-align: middle;
    border: 0;
  }
  .industries_section h2 {
    font-size: 80px;
    color: #e5e5e5;
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
    font-family: "Lato Black";
  }
  @media only screen and (max-width: 595px) {
    .industries_section h2 {
      padding-left: 60px;
      font-size: 65px;
    }
  }

  @media only screen and (max-width: 1300px) {
    .industries_section h2 {
      padding-left: 60px;
      font-size: 88px;
    }
  }

  @media only screen and (max-width: 595px) {
    .industries_section h2 {
      padding-left: 60px;
      font-size: 65px;
    }
  }
  .section {
    padding: 50px 10px;
    position: relative;
    height: 100%;
    box-sizing: border-box;
    margin: 0px;
    background: #fff;
    font-size: 14px;
    line-height: 10px;
    color: #333;
    text-shadow: none;
    font-family: "Lato Heavy";
    overflow: hidden;
  }
</style>
