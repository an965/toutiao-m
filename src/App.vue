<template>
  <div id="app">
    
    <router-view></router-view>
    <h1>黑马头条</h1>
    <i class="iconfont icon-guanbi"></i>
    <van-button type="primary">主要按钮</van-button>
<van-button type="success">成功按钮</van-button>
<van-button type="default">默认按钮</van-button>
<van-button type="warning">警告按钮</van-button>
<van-button type="danger">危险按钮</van-button>
  </div>
</template>
<script>

  export default {
    name: 'App'
  }
</script>

<style lang="less">

</style>
