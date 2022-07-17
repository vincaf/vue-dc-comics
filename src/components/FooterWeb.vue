<template>
  <div id="footer">
    <div id="navbar_footer">
      <div class="container-content d-flex justify-content-between">
        <div class="list">
          <h4>DC COMICS</h4>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>

          <h4>SHOP</h4>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>

          <h4>DC</h4>
          <ul>
            <li>Terms Of Use</li>
            <li>Privacy policy</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>

          <h4>SITES</h4>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <div>
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>

      </div>
    </div>
    <div id="low_footer">

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  #navbar_footer{
    background-image: url("../assets/img/footer-bg.jpg");
    height: 260px;
    background-size: cover;
    overflow: hidden;
  }

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

  #low_footer{
    background-color: #303030;
    height: 95px;
  }
</style>