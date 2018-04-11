<template>
  <div>
    <mheader></mheader>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <span id="stylus">stylus</span>
  </div>
</template>

<script>
  import mheader from './components/main-header/head.vue'
  import tab from './components/main-tab/tab.vue'

  export default {
    components: {
      mheader,
      tab
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "common/stylus/variable.styl"

  #stylus
    color:$color-theme
</style>
