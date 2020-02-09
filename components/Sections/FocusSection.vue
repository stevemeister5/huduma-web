<template>
  <section class="section industries_section">
    <h2 class="slideInUp">
      Our Focus
    </h2>
    <p>
      We're a full-service software provider offering product development and digital transformation services to
      Governments, and Businesses, through data-driven solutions for mobile, cloud, and web platforms.
      Native Application Development.
      <br />
      <a-button class="huduma-red-button">
        KNOW MORE
        <a-icon type="ellipsis" />
      </a-button>
    </p>
    <div>
      <a-row>
        <a-col :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
          <service-card />
        </a-col>
        <a-col :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
          <service-card />
        </a-col>
        <a-col :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
          <service-card />
        </a-col>
      </a-row>
    </div>
  </section>
</template>

<script>
  import ServiceCard from '../ServiceComponents/ServiceCard'

  export default {
    components: {
      ServiceCard
    }
  }
</script>

<style scoped>
  .industries_section {
    background: #f8f8f8;
    overflow: hidden;
    display: block;
    width: 100%;
    box-sizing: border-box;
    height: auto;
  }

  .section {
    padding: 20px 80px 20px 80px;
    /*padding: 50px 10px;*/
    position: relative;
    height: 100%;
    box-sizing: border-box;
    font-size: 14px;
    line-height: 20px;
    color: #333;
    text-shadow: none;
    font-family: "Lato Heavy";
    overflow: hidden;
  }

  .industries_section h2 {
    font-size: 80px;
    color: #e5e5e5;
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bolder;
  }

  @media only screen and (max-width: 595px) {
    .industries_section h2 {
      font-size: 65px;
    }
  }

  @media only screen and (max-width: 1300px) {
    .industries_section h2 {
      font-size: 60px;
    }
  }

  @media only screen and (max-width: 595px) {
    .industries_section h2 {
      font-size: 45px;
    }
  }

  .product_card:hover {
    box-shadow: 0px 3px 10px 1px #ddd;
    -webkit-transform: translateY(-5px);
    -moz-transform: translateY(-5px);
    -ms-transform: translateY(-5px);
    -o-transform: translateY(-5px);
    transform: translateY(-5px);
  }

  .product_card {
    margin: 20px 3% 20px 0px;
    background: #fff;
    box-shadow: none;
    border: none;
    padding: 30px 40px 50px 40px;
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

  @media only screen and (max-width: 768px) {
    .industries_section p {
      color: #585858;
      line-height: 24px;
    }
  }

  @media only screen and (max-width: 900px) {
    .industries_section p {
      color: #585858;
      line-height: 27px;
    }
  }

  @media only screen and (max-width: 1024px) {
    .industries_section p {
      color: #585858;
      line-height: 27px;
    }
  }

  @media only screen and (max-height: 700px) {
    .industries_section p {
      font-size: 12px;
      line-height: 24px;
    }
  }

  @media only screen and (max-width: 1220px) {
    .industries_section p {
      font-size: 12px;
      line-height: 24px
    }
  }

  @media only screen and (max-width: 1450px) {
    .industries_section p {
      font-size: 12px;
    }
  }

  .industries_section p {
    color: #585858;
    line-height: 27px;
  }
</style>
