<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont icon-back">&#xe624;</span>
    </div>
    <div class="header-input"><span class="iconfont icon-search">&#xe632;</span>搜索</div>
    <div class="header-right">城市<span class="iconfont icon-arrow">&#xe62d;</span></div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang='stylus' scoped>
  @import '~styles/varibles.styl'
  .header
    line-height: .86rem
    height: .86rem
    display: flex
    background: $bgColor
    color :#fff
    .header-left
      width: .62rem
      float: left
      .icon-back
        display: block
        text-align: center
        font-size: .4rem
    .header-input
      flex: 1
      height: .64rem
      line-height: .64rem
      background: #fff
      border-radius: .1rem
      margin-top: .12rem
      padding-left: .12rem
      margin-left: .2rem
      color: #ccc
      font-size: .4rem
      .icon-search
        font-size: .4rem
    .header-right
      width: 1.24rem
      text-align: center
      font-size: .3rem
      .icon-arrow
        font-size: .2rem
</style>
