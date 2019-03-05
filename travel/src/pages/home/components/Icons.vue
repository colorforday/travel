<template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
    <div class="icon">
      <div class="icon-img"></div>
      <p class="icon-desc">周边游</p>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Icons"
  }
</script>

<style lang="stylus" scoped>
  .icons {
    display: flex;
    height: 0;
    padding-bottom: 50%;
    overflow: hidden;
    flex-direction: row;
    flex-wrap wrap;
    .icon {
      width: 25%;
      height: 0;
      padding-bottom: 25%;
      background: #fcc;
      text-align: center;
      .icon-img {
        width: 1rem;
        height: 1rem;
        margin: 0 auto;
        margin-top: .2rem;
        margin-bottom: .15rem;
        background: url('../../../assets/images/un_ico_localnav_v7.12@2x.png');
      }
      .icon-desc{
        height:.3rem;
        font-size: .3rem;
      }
    }
  }
</style>
