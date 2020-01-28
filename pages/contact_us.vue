<template>
  <section class="section industries_section">
    <welcome-banner />
    <country-tab />
  </section>
</template>

<script>
    import WelcomeBanner from '../components/ContactComponent/WelcomeBanner'
    import CountryTab from '../components/ContactComponent/CountryTab'

    export default {
        components: {
            WelcomeBanner,
            CountryTab
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
    padding-left: 120px;
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
</style>
