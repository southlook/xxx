<template>
    <div class="header">
        <div class="header-left">
            <div class="iconfont back-icon">&#xe624;</div>
        </div>
        <div class="header-input">
            <span class="iconfont">&#xe632;</span>
            输入城市/景点/游玩主题
        </div>
        <div class="header-right">
            城市
            <span class="iconfont arrow-icon">&#xe64a;</span>
        </div>


    </div>

</template>

<script>
export default {
    name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~@/assets/styles/varibles.styl'
.header
     display:flex
     line-height:$headerHeight
     background:$bgColor
     color:#fff
    .header-left
     width:.64rem
     float:left
    .back-icon
     text-align:center
     font-size:.4rem
    .header-input
      flex:1
      height:.64rem
      line-height:.64rem
      margin-top:.12rem
      margin-left:.2rem
      padding-left:.2rem
      background:#ffffff
      border-radius:.1rem
      color:#ccc
    .header-right
      min-width:1.24rem
      padding:0 .1rem
      float:right
      text-align:center
      font-size:.14rem
    .arrow-icon
      margin-left:-.04rem
      font-size:.24rem

</style>