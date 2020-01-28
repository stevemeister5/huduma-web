<template>
  <a-card class="product_card card_outer">
    <img :src="require('@/assets/images/office/silicondar.jpg')">
    <h2>Huduma Analytics</h2>
    <p>If you are a business owner, you already know the importance of business security. Most of the businesses
      are
      just one ‘security mishap’ away from a temporary or a total failure. Security mishaps come in different
      sizes
      and shapes, such as the occurrence of fire or thefts happening inside your business premises.&nbsp; All
      these
      mishaps</p>
    <a-button class="huduma-red-button"> READ MORE
      <a-icon type="right"/>
    </a-button>
  </a-card>
</template>

<script>
    export default {}
</script>

<style scoped>
  .ant-card-wider-padding .ant-card-body {
    padding: 0 !important;
  }
  .card_outer {
    box-shadow: none;
    border: none;
    padding: 0;
    width: 100%;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
  }
  .card_outer img {
    height: auto;
    width: 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
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
    margin: 20px 3% 20px 0px;
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
    box-shadow: 0px 3px 10px 1px #ddd;
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

  .product_card h2 {
    color: #333;
    font-size: 24px;
    line-height: 30px;
    text-align: left;
    font-family: "Lato Semibold";
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
  }
  .product_card p {
    line-height: 25px;
    font-family: "Lato Light";
    color: #999;
    font-size: 12px;
    text-align: justify;
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
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
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
  }

</style>
