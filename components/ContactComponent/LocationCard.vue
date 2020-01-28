<template>
  <a-card class="loc_card" hoverable style="width: 450px">
    <div class="loc_header">
      <h4 style="font-family: 'Lato Heavy'">TANZANIA</h4>
      <div class="loc_line">
        <div class="loc_outline">
          <div class="loc_innerline">
          </div>
        </div>
      </div>
    </div>
    <div class="loc_body">
      <h4>Huduma Plus</h4>
      <p>Ukonga Ilala,<br> P.O.Box 1992, Dar es salaam<br> Tanzania</p>
      <p style="font-size: 15px;"></p>
      <p style="font-size: 15px;"><a href="" style="color: white;">E: contact@huduma.com</a></p>
    </div>
    <div class="locContentone_footer">
      <div class="loc_map">
        <img class="whitePointer" src="https://accubits.com/wp-content/themes/accubits/images/contact/whitePointer.png">
        <p>View Map</p>
      </div>
      <div class="locoArrow">
        <img class="whiteArrow" src="https://accubits.com/wp-content/themes/accubits/images/contact/whiteArrow.png">
      </div>
    </div>
  </a-card>
</template>

<script>
    export default {
    }
</script>

<style scoped>
  .loc_card {
    background: #e72d31;
    color: #fff;
    font-size: 14px;
    line-height: 20px;
    width: 450px;
    font-family: "Lato Semibold";
  }
  .loc_body {
    padding: 5% 5% 0% 5%;
  }

  .loc_map p {
    margin: 0;
    margin-left: 10px;
    vertical-align: top;
  }
  .loc_map {
    display: flex;
  }
  .loc_innerline {
    height: 5px;
    background: #fff;
    width: 30%;
    position: absolute;
    top: -2px;
    left: 0;
  }
  .loc_outline {
    height: 1px;
    background: #fff;
    width: 100%;
    position: relative;
  }
  .loc_header h4 {
    margin: 30px 20px;
    text-transform: uppercase;
    font-weight: 400;
    font-family: "Lato Semibold";
  }
  h4 {
    color: white;
  }
  .locContentone_footer {
    display: flex;
    justify-content: space-between;
    padding: 20px;
  }
</style>
