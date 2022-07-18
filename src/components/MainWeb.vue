<template>
  <div>
    <div id="main">
      <div class="container-content">
        <h5 class="text-white py-5 fw-bold mb-0">--> Content goes here</h5> 
      </div>
    </div>
    <div id="bluebar">
      <div class="container-content d-flex justify-content-around py-5">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="DIGITAL COMICS">
          <span>DIGITAL COMICS</span>
        </div>
        <div>
          <img src="../assets/img/buy-comics-merchandise.png" alt="DC MERCHANDISE">
          <span>DC MERCHANDISE</span>
        </div>
        <div>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="SUBSCRIPTION">
          <span>SUBSCRIPTION</span>
        </div>
        <div>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="COMIC SHOP LOCATOR">
          <span>COMIC SHOP LOCATOR</span>
        </div>
        <div>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="DC POWER VISA">
          <span>DC POWER VISA</span>
        </div>
      </div>
    </div>    
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  #main{
    background-color: #1c1c1c;
  }

  #bluebar{
    background-color: #0282f9;
    color: #fff;

    img{
      height: 40px;
    }

    span{
      padding: 0 10px;
      font-size: 12px;
    }
  }
</style>