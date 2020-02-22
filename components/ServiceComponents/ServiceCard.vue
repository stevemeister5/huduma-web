<template>
  <a-card class="service" hoverable style="max-width: 100%">
    <div
      :style="{ backgroundImage: 'url(' + require('@/assets/images/neural.svg') + ')' }"
      class="icon"/>
    <h3>Artificial Intelligence</h3>
    <p>We are helping businesses enable to laverage AI in their existing system and drive profitable results.</p>
    <a-button class="cap_more" type="link" ghost>
      VIEW MORE
    </a-button>
  </a-card>
</template>

<script>
  export default {
    name: 'ServiceCard',
    props: {
      serviceType: {
      }
    }
  }
</script>

<style scoped>
  @import '../../assets/css/service_card.css';
</style>
