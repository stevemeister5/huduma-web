<template>
  <a-card class="product_card card_outer">
    <h3>{{ username }}</h3>
    <img :src="imageProfile">
    <p>{{ description }}</p>
  </a-card>
</template>

<script>
  export default {
    props: {
      imageProfile: String,
      username: String,
      description: String
    }
  }
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
  }

  .product_card h3 {
    text-transform: uppercase;
    color: #000;
    font-size: 16px;
    text-align: justify;
    font-style: normal;
    font-weight: bolder;
    line-height: 20px;
    font-family: "Lato Heavy";
  }

  .product_card p {
    color: #191919;
    font-size: 14px;
    line-height: 1.4em;
    overflow: hidden;
    font-family: "Lato Medium";
  }

  @media only screen and (max-height: 750px) {
    .case_detail h3 {
      font-size: 12px;
    }
  }
</style>
