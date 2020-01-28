<template>
  <section class="section industries_section">
    <a-row class="section_outer">
      <a-col
        class="service_left"
             :xs="24"
             :sm="24"
             :md="12"
             :lg="8"
             :xl="8">
        <h2 class="slideInUp">Services</h2>
        <p>We offer integrated consulting and technology implementation services to businesses that want to increase their growth through digital transformation.</p>
        <div class="title_wrap">
          <h2>SERVICES</h2>
        </div>
      </a-col>
      <a-col :xs="24" :sm="24" :md="12" :lg="16" :xl="16">
        <a-row>
          <a-col :xs="24" :sm="24" :md="24" :lg="12" :xl="12">
            <service-card />
          </a-col>
          <a-col :xs="24" :sm="24" :md="24" :lg="12" :xl="12">
            <service-card />
          </a-col>
          <a-col :xs="24" :sm="24" :md="24" :lg="12" :xl="12">
            <service-card />
          </a-col>
          <a-col :xs="24" :sm="24" :md="24" :lg="12" :xl="12">
            <service-card />
          </a-col>
        </a-row>
      </a-col>
    </a-row>

  </section>
</template>

<script>
    import ServiceCard from '../components/ServiceComponents/ServiceCard'
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
    padding: 50px 10px;
    position: relative;
    height: 100%;
    box-sizing: border-box;
    margin: 0px;
    background: #fff;
    font-size: 14px;
    line-height: 20px;
    color: #333;
    text-shadow: none;
    font-family: "Lato Heavy";
    overflow: hidden;
  }

  .industries_section h2 {
    font-size: 108px;
    color: #e5e5e5;
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bolder;
  }
  @media only screen and (max-width: 595px) {
    .service_left {
      display: none;
    }
    .industries_section h2 {
      font-size: 65px;
    }
  }

  @media only screen and (max-width: 1300px) {
    .industries_section h2 {
      font-size: 88px;
    }
  }

  @media only screen and (max-width: 595px) {
    .service_left {
      display: none;
    }
    .industries_section h2 {
      font-size: 65px;
    }
  }

  .industries_section p {
    font-family: "Lato Medium";
    padding-left: 20px;
    padding-right: 20px;
    line-height: 24px;
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
  }

  .title_wrap {
    background: #f4f4f4;
    padding: 55px 0;
    margin: 30px 0;
  }

  .title_wrap h2 {
    box-sizing: border-box;
    width: 250px;
    color: #ebebeb;
    white-space: pre-wrap;
    word-wrap: break-word;
    line-height: 80px;
    height: 100px;
    margin: 0 0;
    font-size: 70px;
    font-weight: bold;
    padding-left: 80px;
  }

  .service_left {
    padding-left: 40px;
    padding-right: 50px;
  }
</style>
