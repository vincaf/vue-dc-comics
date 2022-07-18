<template>
  <div id="footer">
    <div id="navbar_footer">
      <div class="container-content d-flex justify-content-between">
        <div class="list">
          <div>
            <h4>DC COMICS</h4>
            <ul>
              <li v-for="(link, index) in dcComicsList" :key="index">{{link.name}}</li>
            </ul>
          </div>

          <div>
            <h4>SHOP</h4>
            <ul>
              <li v-for="(link, index) in shopList" :key="index">{{link.name}}</li>
            </ul>
          </div>

          <div>
            <h4>DC</h4>
            <ul>
              <li v-for="(link, index) in dcList" :key="index">{{link.name}}</li>
            </ul>
          </div>

          <div>
            <h4>SITES</h4>
            <ul>
              <li v-for="(link, index) in sitesList" :key="index">{{link.name}}</li>
            </ul>
          </div>
        </div>

        <div>
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>

      </div>
    </div>
    <div id="low_footer">
      <div class="container-content d-flex justify-content-between">
        <div class="py-4">
          <button>SIGN-UP NOW!</button>
        </div>

        <div class="d-flex py-4 align-items-center">
          <div class="follow-us">FOLLOW US</div>
          <div class="icon"><img src="../assets/img/footer-facebook.png" alt="facebook"></div>
          <div class="icon"><img src="../assets/img/footer-twitter.png" alt="facebook"></div>
          <div class="icon"><img src="../assets/img/footer-youtube.png" alt="facebook"></div>
          <div class="icon"><img src="../assets/img/footer-pinterest.png" alt="facebook"></div>
          <div class="icon"><img src="../assets/img/footer-periscope.png" alt="facebook"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentMain',
  data: function() {
    return {
      dcComicsList: [
        {
          name: "Character", 
          url: "#",
        },
        {
          name: "Comics", 
          url: "#",
        },
        {
          name: "Movies", 
          url: "#",
        },
        {
          name: "TV", 
          url: "#",
        },
        {
          name: "Games", 
          url: "#",
        },
        {
          name: "Videos", 
          url: "#",
        },
        {
          name: "News", 
          url: "#",
        },
      ],
      shopList: [
        {
          name: "Shop DC", 
          url: "#",
        },
        {
          name: "Shop DC Collectibles", 
          url: "#",
        },
      ],
      dcList: [
        {
          name: "Terms Of Use", 
          url: "#",
        },
        {
          name: "Privacy policy (New)", 
          url: "#",
        },
        {
          name: "Ad Choices", 
          url: "#",
        },
        {
          name: "Advertising", 
          url: "#",
        },
        {
          name: "Jobs", 
          url: "#",
        },
        {
          name: "Subscriptions", 
          url: "#",
        },
        {
          name: "Talent Workshops", 
          url: "#",
        },
        {
          name: "CPSC Certificates", 
          url: "#",
        },
        {
          name: "Ratings", 
          url: "#",
        },
        {
          name: "Shop Help", 
          url: "#",
        },
        {
          name: "Contact Us", 
          url: "#",
        },
      ],
      sitesList: [
        {
          name: "DC", 
          url: "#",
        },
        {
          name: "MAD Magazine", 
          url: "#",
        },
        {
          name: "DC Kids", 
          url: "#",
        },
        {
          name: "DC Universe", 
          url: "#",
        },
        {
          name: "DC Power Visa", 
          url: "#",
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  #navbar_footer{
    background-image: url("../assets/img/footer-bg.jpg");
    height: 265px;
    background-size: cover;
    overflow: hidden;

    .list{
    max-width: 400px;
    display: flex;
    align-items: flex-start;
    max-height: 290px;
    flex-flow: column wrap;
    font-size: 10px;
    padding: 20px 0;
    
    h4{
        font-size: 17px;
        color: #fff;
        font-stretch: extra-condensed;
        font-weight: bold;
    }

    li{
      color: #7f7f83;
      list-style: none;
    }

    ul{
      padding-left: 0;
      margin-right: 25px;
      margin-bottom: 29px;
    }
  }

    img{
    height: 430px;
    position: relative;
    top: -90px;
    }
  }

  #low_footer{
    background-color: #303030;
    height: 95px;

    button{
      border: 2px solid #0282f9;
      background-color: #303030;
      color: #fff;
      font-size: 14px;
      padding: 10px;
    }

    .follow-us{
      color: #0282f9;
      font-weight: bold;
    }

    .icon{
      margin-left: 15px;
    }
  }
</style>