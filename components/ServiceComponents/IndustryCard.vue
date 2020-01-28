<template>
  <a-card class="product_card card_outer" hoverable style="max-width: 100%">
    <div
      class="icon"
      :style="{ backgroundImage: 'url(' + require('@/assets/images/neural.svg') + ')' }"></div>
    <h3>Retail</h3>
    <p>
      We work with leading global retailers to transform their business models
    </p>
  </a-card>
</template>

<script>
    export default {}
</script>

<style scoped>
  @import '../../assets/css/product_card.css';
</style>
