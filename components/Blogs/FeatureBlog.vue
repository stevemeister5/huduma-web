<template>
  <a-card style="padding: 0" class="product_card card_outer ant-card-body ">
    <div
      class="feature-wrapper">
      <div style="width: 100%">
        <div
          class="feature_image"
             style="background-image: url('https://blog.accubits.com/wp-content/uploads/2019/05/Artboard-1.png')"></div>
        <div
          class="feature_details">
          <h2>Artificial Intelligence For Enhancing Business Security</h2>
          <p></p>
          <p>If you are a business owner, you already know the importance of business security. Most of the businesses
            are
            just one ‘security mishap’ away from a temporary or a total failure. Security mishaps come in different
            sizes
            and shapes, such as the occurrence of fire or thefts happening inside your business premises.&nbsp; All
            these
            mishaps […]</p>
          <a-button class="huduma-red-button"> READ MORE
            <a-icon type="right"/>
          </a-button>
        </div>
      </div>
    </div>
  </a-card>
</template>

<script>
    export default {}
</script>

<style scoped>
  .card_outer {
    box-shadow: none;
    border: none;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    overflow: hidden;
    z-index: 1;
    -webkit-flex-shrink: 0;
    -ms-flex: 0 0 auto;
    flex-shrink: 0;
    width: 100%;
    height: 100%;
  }

  .card_outer img {
    height: auto;
    width: 100%;
  }
  .product_card {
    background: #fff;
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

  .product_card:hover {
    box-shadow: 0px 3px 10px 1px #ddd;
    -webkit-transform: translateY(-5px);
    -moz-transform: translateY(-5px);
    -ms-transform: translateY(-5px);
    -o-transform: translateY(-5px);
    transform: translateY(-5px);
  }

  .product_card .work_image {
    height: auto;
    background: no-repeat center;
    background-size: contain;
    /* box-shadow: 0 6px 12px rgba(0, 0, 0, 0.05), 0 10px 20px rgba(0, 0, 0, 0.10);
    border-radius: 50%; */
  }

  .product_card p {
    color: #191919;
    font-size: 15px;
    text-align: center;
    line-height: 25px;
    font-family: "Lato Light";
  }
  .feature_image {
    display: inline-block;
    vertical-align: top;
    width: 40%;
    height: 450px;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
  }
  .feature_details {
    width: 60%;
    padding: 15% 5%;
    margin-left: -4px;
    display: inline-block;
    vertical-align: top;
    box-sizing: border-box;
  }

  .feature-wrapper {
    position: relative;
    width: 100%;
    height: 100%;
    z-index: 1;
    display: -webkit-box;
    display: -moz-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-transition-property: -webkit-transform;
    -moz-transition-property: -moz-transform;
    -o-transition-property: -o-transform;
    -ms-transition-property: -ms-transform;
    transition-property: transform;
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
  }
  .feature_details p {
    color: #999;
    font-family: "Lato Light";
    font-size: 12px;
    /* height: 120px; */
    overflow: hidden;
    text-align: justify;
  }

  .feature_details h2 {
    font-family: "Lato Heavy";
    font-size: 18px;
    line-height: 22px;
    color: #333;
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
  .ant-card-body {
    padding: 0!important;
    zoom: 1;
  }

  .ant-card-wider-padding .ant-card-body {
    padding: 0;
  }
</style>
