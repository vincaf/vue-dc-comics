<template>
  <div id="app">
    <HeaderWeb />
    <MainWeb />
    <FooterWeb />
  </div>
</template>

<script>
import HeaderWeb from './components/HeaderWeb.vue';
import MainWeb from './components/MainWeb.vue';
import FooterWeb from './components/FooterWeb.vue';

export default {
  name: 'App',
  components: {
    HeaderWeb,
    MainWeb,
    FooterWeb,
  }
}
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap.scss";

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  .container-content{
    max-width: 1000px;
    margin: 0 auto;
  }
</style>
