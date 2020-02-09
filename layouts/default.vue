<template>
  <div>
    <a-layout-header
      :style="{ position: 'fixed', zIndex: 1,
                width: '100%',
                background: '#FFF',
                transition: 'background-color 0.4s ease-out'}"
    >
      <navigation-bar />
    </a-layout-header>
    <a-layout-content>
      <nuxt />
    </a-layout-content>
    <a-layout-footer class="footer_section">
      <reach-us-form />
      <section>
        <div class="copyright_wrap">
          © Huduma Plus 2020. All Rights Reserved.
        </div>
      </section>
    </a-layout-footer>
  </div>
</template>
<script>
    import NavigationBar from '../components/NavigationBar'
    import ReachUsForm from '../components/ContactComponent/ReachUsForm'
  export default {
      components: {
          NavigationBar,
          ReachUsForm
      }
  }
</script>
<style>
  html {
    display: block;
    margin: 0;
    padding: 0;
  }
  body html {
    overflow: visible;
    height: initial;
  }
  body {
    margin: 0px;
    font-family: "Lato Medium";
    font-max-size: 14px;
    line-height: 20px;
    color: #333333;
    text-shadow: none;
  }
  .footer_section {
    position: relative;
    background: #313439;
    padding: 10px 40px;
    box-sizing: border-box;
  }
  .copyright_wrap {
    background: #2d3034;
    padding: 10px 120px;
    color: #a4a4a4;
    font-size: 12px;
    font-family: "Lato Light";
    position: absolute;
    width: 100%;
    left: 0;
    bottom: 0;
    box-sizing: border-box;
  }
  .ant-layout-header {
    height: fit-content;
    padding: 0;
    line-height: 64px;
  }
</style>
