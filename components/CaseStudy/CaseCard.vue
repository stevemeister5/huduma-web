<template>
  <a-card class="card_outer">
    <h1>Retail</h1>
    <div class="case_field">Retail</div>
    <div class="case_title">Facility Management</div>
    <div class="case_field_wrap">
      <ul>
        <li>Artificial Intelligence</li>
      </ul>
    </div>
    <div class="focus_area">
      <div class="area_item">
        <div class="area_icon area_mobile"></div>
        <p>MOBILE <a-icon type="tablet" /></p>
      </div>
      <div class="area_item">
        <div class="area_icon area_web"></div>
        <p>WEB <a-icon style="color: #ef0d33" type="desktop" /></p>
      </div>
    </div>
    <div class="case_hint">For our client, a prominent exhibition organizer based in Dubai, we built an AI-based
      solution for efficient facility management. Optimal facility management makes a business to enhance user and
      employee experience inside business premises through optimal resource planning, space optimization, facility
      coordination, facility improvement etc.
    </div>
  </a-card>
</template>

<script>
    export default {}
</script>

<style scoped>
  .card_outer {
    box-shadow: none;
    border: none;
    background: #fff;
    margin: 30px 0 0;
    display: inline-block;
    padding: 24px 24px 24px 0px;
    width: 100%;
    white-space: normal;
    /*transition: all 0.5s;*/
    vertical-align: top;
  }
  .card_outer img {
    height: auto;
    width: 100%;
  }

  .card_outer ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .card_outer li {
    display: inline;
    position: relative;
    padding-left: 15px;
    padding-right: 15px;
    text-transform: uppercase;
    font-size: 11px;
    color: rgba(0, 0, 0, 0.6);
  }

  .card_outer li:before {
    content: '';
    position: absolute;
    top: 5px;
    left: 0px;
    width: 5px;
    height: 5px;
    border-radius: 50%;
    background: #ef0d33;
  }

  .card_outer h1 {
    font-size: 120px;
    color: #f5f5f5;
    margin: 0;
    margin-left: 30px;
    font-family: "Lato Heavy";
    line-height: 0;
    white-space: nowrap;
  }
  .case_field {
    color: #fff;
    display: inline-block;
    padding: 3px 15px;
    background: #ef0d33;
    text-transform: uppercase;
    margin: 0 40px 0 40px;
    font-family: "Lato Light";
    font-size: 11px;
    margin-top: -20px;
    margin-bottom: 20px;
  }

  .case_title {
    font-size: 4em;
    font-family: "Lato Heavy";
    line-height: 1.0em;
    color: #000000;
    margin: 0 40px 0 40px;
    display: -webkit-box;
    text-align: left;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  .focus_area {
    padding: 10px;
    margin: 20px 0px 0px 0px;
    display: block;
  }

  .area_icon {
    background: no-repeat center;
    background-size: contain;
    position: absolute;
    margin: 8px;
    left: 0;
    top: 8px;
  }

  .area_item {
    display: inline-block;
    position: relative;
  }

  .case_hint {
    color: black;
    line-height: 1.8;
    font-size: 14px;
    position: relative;
    width: 75%;
    text-align: justify;
    display: -webkit-box;
    padding: 10px;
    -webkit-line-clamp: 10;
    -webkit-box-orient: vertical;
    overflow: hidden;
    /*text-overflow: ellipsis;*/
    box-sizing: border-box;
    font-family: "Lato Light";
  }
  .area_web {
    color: #ef0d33;
  }
  .area_item {
    margin-right: 8px;
  }
  .case_field_wrap {
    background: #f3f3f3;
    padding: 20px 80px 20px 100px;
    margin: 30px 0 0;
  }
</style>
