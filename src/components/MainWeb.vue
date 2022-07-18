<template>
  <div>
    <div id="main">
      <div class="jumbotron">
        <div class="current-series">CURRENT SERIES</div>
      </div>

      <div class="container-content mt-5">
        <div class="d-flex flex-wrap px-3 mb-3">
          <ComicsCard v-for="(comic, index) in comics" :key="index"
          :imageUrl="comic.thumb"
          :title="comic.series"
          />
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
import ComicsCard from './ComicsCard.vue';

export default {

  name: 'MainWeb',
  components: {
    ComicsCard,
  },

  data: function(){
    return{
      comics:[
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          "price": "$19.99",
          "series": "Action Comics",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          "price": "$3.99",
          "series": "American Vampire 1976",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          "price": "$16.99",
          "series": "Aquaman",
          "type": "graphic novel"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          "price": "$2.99",
          "series": "Batgirl",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          "price": "$3.99",
          "series": "Batman",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          "price": "$2.99",
          "series": "Batman Beyond",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          "price": "$3.99",
          "series": "Batman/Superman",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          "price": "$4.99",
          "series": "Batman/Superman Annual",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          "price": "$5.99",
          "series": "Batman: The Joker War Zone",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          "price": "$6.99",
          "series": "Batman: Three Jokers",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          "price": "$4.99",
          "series": "Batman: White Knight Presents: Harley Quinn",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          "price": "$16.99",
          "series": "Catwoman",
          "type": "graphic novel"
        }
      ]
    }
  }
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

  .load{
    color: #fff;
    background-color: #0282f9;
    font-size: 12px;
    font-weight: bold;
    width: 150px;
    padding: 5px 20px;
    text-align: center;
    margin: 0 auto;
    cursor: pointer;
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