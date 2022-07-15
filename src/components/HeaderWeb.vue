<template>
  <div id="header" class="container-content">
    <div class="d-flex justify-content-between align-items-center">
      <img src="../assets/img/dc-logo.png" alt="dc logo">
      <ul>
        <li>CHARACTERS</li>
        <li class="active">COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  #header{
    background-color: #fff;
  }

  img{
    width: 80px;
    padding: 15px 0;
  }

  ul{
    margin: 0;
  }

  li{
    display: inline-block;
    list-style: none;
    padding: 10px;
    font-size: 11px;
    font-weight: bold;
    color: #58534d;
    cursor: pointer;

    &.active{
      color: #0282f9;
      border-bottom: 3px solid #0282f9;
    }

    &:hover{
      background-color: #f1f8ff;
    }
  }
</style>