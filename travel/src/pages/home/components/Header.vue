<template>
  <div class="header">
    <div class="header-left">
      <i class="iconfont back-icon">&#xe660;</i>
    </div>
    <div class="header-input">
      <i class="iconfont">&#xe651;</i>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市 <i class="iconfont arrow-icon">&#xe65c;</i>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HomeHeader'
  }
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header {
    display: flex;
    height: 0.86rem;
    line-height: 0.86rem;
    background: $bgColor;
    color: #fff;
    .header-left {
      width: 0.64rem;
      float: left;
      text-align: center;
      .back-icon {
        font-size: .4rem;
      }
    }
    .header-input {
      flex: 1;
      height: 0.64rem;
      line-height: .64rem;
      margin-top: .1rem;
      margin-right: .2rem;
      background: $white;
      border-radius: .1rem;
      color: #ccc;
      padding: 0 .2rem;
    }
    .header-right {
      /*width: 1.24rem;*/
      float: right;
      text-align: center;
      .arrow-icon {
        font-size: .24rem;
        margin-right: .2rem;
      }
    }
  }


</style>
