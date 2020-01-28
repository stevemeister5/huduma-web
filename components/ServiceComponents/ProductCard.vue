<template>
  <a-card class="product_card card_outer" hoverable style="max-width: 100%" size="small">
    <div
      class="icon"
      :style="{ backgroundImage: 'url(' + require('@/assets/images/neural.svg') + ')' }"></div>
    <h3>Huduma Analytics</h3>
    <p>Huduma Analytics is an AI-powered Sentiment analysis software that enables businesses to harness intelligent insights of users data behaviour</p>
    <h4 class="card_category">BI - SENTIMENT ANALYSIS</h4>
  </a-card>
</template>

<script>
    export default {
        name: "ProductCard"
    }
</script>

<style scoped>
  @import '../../assets/css/product_card.css';
</style>
