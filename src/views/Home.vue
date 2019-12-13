<template>
  <div class="container">
    <div class="img">
      <img id="img" src="@/assets/main.png" alt="">
      <div class="block-one" @click="tolink('https://www.vcloudshop.com/wx/15')"></div>
      <div class="block-tow" @click="tolink('https://www.vcloudshop.com/wx/15')"></div>
      <div class="block-three" @click="tolink('https://www.vcloudshop.com/wx/15')"></div>
      <div class="block-four" @click="tolink('https://www.vcloudshop.com/wxprocess/')"></div>
      <div class="block-five" @click="tolink('http://www.vcloudshop.com/manager\n')"></div>
      <div class="block-six" @click="tolink('http://www.vcloudshop.com/admin')"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {

    }
  },
  methods: {
    tolink (url) {
      window.open(url)
    }
  },
  components: {},
  created () {

  }
}
</script>

<style scoped>
  .container {
    width: 1200px;
    margin: 0 auto;
  }

  .img {
    position: relative;
    width: 1200px;
  }

  img {
    height: 100vh;
    margin: 0 auto;
    display: block;
  }

  .block-one {
    position: absolute;
    width: calc((624 / 895) * 100vh);
    height: calc((62 / 896) * 100vh);
    left: calc(600px - ((244 / 994.44) * ((994.44 / 895) * 100vh)));
    top: calc((132 / 896) * 100vh);
    cursor: pointer;
  }

  .block-tow {
    position: absolute;
    width: calc((110 / 895) * 100vh);
    height: calc((50 / 895) * 100vh);
    left: calc(600px - ((244 / 994.44) * ((994.44 / 895) * 100vh)));
    top: calc((324 / 895) * 100vh);
    cursor: pointer;
  }

  .block-three {
    position: absolute;
    width: calc((110 / 895) * 100vh);
    height: calc((50 / 895) * 100vh);
    top: calc((324 / 895) * 100vh);
    left: calc(600px - ((128 / 994.44) * ((994.44 / 895) * 100vh)));
    cursor: pointer;
  }

  .block-four {
    position: absolute;
    width: calc((110 / 895) * 100vh);
    height: calc((50 / 895) * 100vh);
    top: calc((324 / 895) * 100vh);
    left: calc(600px - ((12 / 994.44) * ((994.44 / 895) * 100vh)));
    cursor: pointer;
  }

  .block-five {
    position: absolute;
    width: calc((624 / 895) * 100vh);
    height: calc((62 / 896) * 100vh);
    left: calc(600px - ((244 / 994.44) * ((994.44 / 895) * 100vh)));
    top: calc((478 / 896) * 100vh);
    cursor: pointer;
  }

  .block-six {
    position: absolute;
    width: calc((624 / 895) * 100vh);
    height: calc((62 / 896) * 100vh);
    left: calc(600px - ((244 / 994.44) * ((994.44 / 895) * 100vh)));
    top: calc((666 / 896) * 100vh);
    cursor: pointer;
  }
</style>
