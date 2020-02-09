<template>
  <div>
    <a-menu
      :style='{backgroundColor: navColor}'
      @scroll='handleScroll'
            v-model='current'
            mode='horizontal'>
      <a-menu-item>
        <img height="64" :src="require('@/assets/images/logos/huduma_full.png')">
      </a-menu-item>
      <a-menu-item key="home">
        <nuxt-link to="/">
          <a-icon type='home'/>
          Home
        </nuxt-link>
      </a-menu-item>
      <a-menu-item key="service">
        <nuxt-link to="/services">
          <a-icon type='rocket'/>
          Services
        </nuxt-link>
      </a-menu-item>
<!--      <a-menu-item key="products">-->
<!--        <nuxt-link to="/products">-->
<!--          <a-icon type='appstore'/>-->
<!--          Products-->
<!--        </nuxt-link>-->
<!--      </a-menu-item>-->
<!--      <a-menu-item key="case">-->
<!--        <nuxt-link to="/case_studies">-->
<!--          <a-icon type='trophy'/>-->
<!--          Case study-->
<!--        </nuxt-link>-->
<!--      </a-menu-item>-->
<!--      <a-menu-item key="industry">-->
<!--        <nuxt-link to="/industries">-->
<!--          <a-icon type='branches'/>-->
<!--          Industries-->
<!--        </nuxt-link>-->
<!--      </a-menu-item>-->
      <a-menu-item key='contact'>
        <nuxt-link to="/contact_us">
          <a-icon type='mail'/>
          Contact Us
        </nuxt-link>
      </a-menu-item>
      <a-menu-item key='careers'>
        <nuxt-link to="/careers">
          <a-icon type='mail'/>
          Careers
        </nuxt-link>
      </a-menu-item>
    </a-menu>
  </div>
</template>
<script>
    export default {
        data () {
            return {
                current: ['mail'],
                navColor: '#00000000'
            }
        },
        created () {
            window.addEventListener('scroll', this.handleScroll)
        },
        destroyed () {
            window.removeEventListener('scroll', this.handleScroll)
        },
        methods: {
            handleScroll (event) {
                if (window.screenTop === 0) {
                    this.navColor = '#00000000'
                } else {
                    this.navColor = '#00000000'
                }
            }
        }
    }
</script>

<style scoped>
  .ant-menu-horizontal > .ant-menu-item:hover, .ant-menu-horizontal > .ant-menu-submenu:hover, .ant-menu-horizontal > .ant-menu-item-active, .ant-menu-horizontal > .ant-menu-submenu-active, .ant-menu-horizontal > .ant-menu-item-open, .ant-menu-horizontal > .ant-menu-submenu-open, .ant-menu-horizontal > .ant-menu-item-selected, .ant-menu-horizontal > .ant-menu-submenu-selected {
    color: #ef0d33;
    border-bottom: 2px solid #ef0d33;
  }
  .ant-menu-item:hover, .ant-menu-item-active, .ant-menu:not(.ant-menu-inline) .ant-menu-submenu-open, .ant-menu-submenu-active, .ant-menu-submenu-title:hover {
    color: #ef0d33;
  }
  .ant-menu-horizontal {
    border: none;
  }
  .ant-layout-header {
    height: inherit;
  }
</style>
