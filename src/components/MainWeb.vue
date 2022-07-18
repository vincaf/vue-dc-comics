<template>
  <div>
    <div id="main">
      <div class="jumbotron">
        <div class="current-series">CURRENT SERIES</div>
      </div>

      <div class="container-content mt-5">
        <div class="d-flex flex-wrap px-3 mb-3">
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
          <div class="comics-container">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div class="title">ACTION COMIC</div>
          </div>
        </div>
        <div class="py-3">
          <div class="load">LOAD MORE</div>
        </div>
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
  .jumbotron{
    width: 100%;
    height: 320px;
    background-image: url("../assets/img/jumbotron.jpg");
    background-size: cover;
    position: relative;

    .current-series{
      background-color: #0282f9;
      color: #fff;
      width: 165px;
      padding: 10px;
      font-weight: bold;
      position: absolute;
      top: 300px;
      left: 260px;
    }
  }

  #main{
    background-color: #1c1c1c;
  }

  .comics-container{
    margin: 10px;
    width: calc((100% / 6) - 20px);

    img{
      width: 150px;
      height: 150px;
      object-fit: cover;
    }

    .title{
      color: #fff;
      margin-top: 5px;
      font-size: 12px;
    }
  }

  .load{
    color: #fff;
    background-color: #0282f9;
    font-size: 12px;
    font-weight: bold;
    width: 150px;
    padding: 5px 20px;
    text-align: center;
    margin: 0 auto;
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