<template>
  <div id="app">
    <!-- 左边菜单栏 -->
    <left-menu></left-menu>

    <div class="r-content">
      <!-- Button按钮 -->
      <div id="comp-btn">
        <vc-button>Button</vc-button>
      </div>
    </div>
  </div>
</template>

<script>
import LeftMenu from './LeftMenu'
import VcButton from './button'

export default {
  name: 'app',
  components: {
    LeftMenu,
    VcButton
  }
}
</script>

<style lang="less">
* {
  margin: 0;
  padding: 0;
}
.r-content{
  margin-left: 200px
}
</style>
