<template>
  <div id="header" class="container-content">
    <div class="d-flex justify-content-between align-items-center">
      <img src="../assets/img/dc-logo.png" alt="dc logo">
      <ul>
        <li v-for="(nav, index) in menuList" :key="index" :class="{'active' : nav.active}">{{nav.name}}</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderWeb',
  data: function (){
    return {
      menuList: [
        {
          name: 'Characters',
          url: '#',
          active: false,
        },
        {
          name: 'Comics',
          url: '#',
          active: true,
        },
        {
          name: 'Movies',
          url: '#',
          active: false,
        },
        {
          name: 'TV',
          url: '#',
          active: false,
        },
        {
          name: 'Games',
          url: '#',
          active: false,
        },
        {
          name: 'Collectibles',
          url: '#',
          active: false,
        },
        {
          name: 'Videos',
          url: '#',
          active: false,
        },
        {
          name: 'Fans',
          url: '#',
          active: false,
        },
        {
          name: 'News',
          url: '#',
          active: false,
        },
        {
          name: 'Shop',
          url: '#',
          active: false,
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  #header{
    background-color: #fff;
  }

  img{
    width: 70px;
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