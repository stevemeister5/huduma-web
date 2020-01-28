<template>
  <a-card class="product_card card_outer">
    <h3>Huduma Analytics</h3>
    <p>For National Election Councel</p>
    <img :src="require('@/assets/images/neural.svg')">
  </a-card>
</template>

<script>
    export default {}
</script>

<style scoped>
  .card_outer {
    box-shadow: none;
    border: none;
  }
  .card_outer img {
    height: auto;
    width: 100%;
  }
  .card_category{
    /* text-transform: uppercase; */
    color: #52535a;
    font-family: montserrat_regular, sans-serif;
    position: absolute;
    bottom: 10px;
    left: 40px;
  }
  .card_category span{
    text-transform: uppercase;
    color: #999;
    font-family: montserrat_regular, sans-serif;
  }
  .product_card {
    background: #fff;
    box-sizing: border-box;
    -webkit-transition: all 0.8s;
    -moz-transition: all 0.8s;
    -ms-transition: all 0.8s;
    -o-transition: all 0.8s;
    transition: all 0.8s;
    cursor: pointer;
    position: relative;
    display: block;
  }
  .product_card:hover {
    box-shadow: none;
    -webkit-transform: translateY(-5px);
    -moz-transform: translateY(-5px);
    -ms-transform: translateY(-5px);
    -o-transform: translateY(-5px);
    transform: translateY(-5px);
  }
  .product_card .work_image  {
    height: auto;
    background: no-repeat center;
    background-size: contain;
    /* box-shadow: 0 6px 12px rgba(0, 0, 0, 0.05), 0 10px 20px rgba(0, 0, 0, 0.10);
    border-radius: 50%; */
  }

  .product_card h3 {
    text-transform: uppercase;
    color: #000;
    font-size: 20px;
    text-align: center;
    font-style: normal;
    font-weight: bolder;
    line-height: 30px;
    font-family: "Lato Heavy";
    margin: 15px auto;
  }

  .product_card p {
    color: #191919;
    font-size: 14px;
    line-height: 30px;
    text-align: center;
    overflow: hidden;
    font-family: "Lato Medium";
  }

  @media only screen and (max-height: 750px) {
    .case_detail h3 {
      font-size: 18px;
    }
  }
</style>
