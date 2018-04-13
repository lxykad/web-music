<template>
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">music</h1>
  </div>
</template>

<script>

  export default {
    data () {
      return {}
    },
    methods: {
      click () {
      }
    },
    created: function () {

    }
  }

</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/variable.styl"
  @import "../../common/stylus/mixin.styl"
  .m-header
    position relative
    height 44px
    background-color darkcyan
    text-align center
    font-size 0
    .icon
      display inline-block
      vertical-align top
      margin-top 6px
      width 30px
      height 30px
      bg-image('logo')
      background-size 30px 30px
    .text
      display inline-block
      vertical-align top
      line-height 44px
      font-size 16px
      background-color aliceblue
</style>
