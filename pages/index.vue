<template>
  <div id="container">
    <item-slider />
    <focus-section />
  </div>
</template>

<script>
  import ItemSlider from '../components/ItemSlider'
  import FocusSection from '../components/Sections/FocusSection'
    export default {
        components: {
            ItemSlider,
            FocusSection
        }
    }
</script>

<style scoped>
</style>
