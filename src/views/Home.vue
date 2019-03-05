<template>
  <div class="home">
    <!--<div id="read"></div>-->
    <span class="icon-clock"></span>
    <span class="text">adsadf</span>
  </div>
</template>

<script>
  // @ is an alias to /src
  import Epub from 'epubjs'

  global.ePub = Epub
  export default {
    name: 'home',
    components: {},
    mounted () {

    }
  }
</script>
<style scoped>
.icon-clock {
  font-size: 20px;
  color: red;
}
  .text {
    font-family: "Days One";
    font-size: 20px;
  }
</style>
