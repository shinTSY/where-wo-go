<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩内容
    </div>
    <div class="header-right">
      城市
    <span class="iconfont arrow-down">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HomeHeader',
  }
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'

  .header
    display flex
    align-items center
    background $bgColor
    color #fff
    .header-left
      width .64rem
      float left
      .back-icon
        text-align center
    .header-input
      flex 1
      line-height .64rem
      margin-left .2rem
      margin-top .12rem
      margin-bottom  .12rem
      padding-left .2rem
      background #ffffff
      border-radius .1rem
      color #ccc
    .header-right
      width 1.24rem
      float right
      text-align center
      .arrow-down
        margin-left -.04rem
        font-size .24rem
</style> 