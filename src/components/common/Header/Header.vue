<template>
  <div class="header">
    <div class="head-logo l"><a class="icon-logo"><i class="ivuicon ivuicon-logo"></i></a></div>
    <div class="head-icon l">
      <a href="#" class="icon-gl_sosuo"><i class="ivuicon ivuicon-gl_sosuo"></i></a>
      <a href="#" class="icon-gl_gongneng"><i class="ivuicon ivuicon-gl_gongneng"></i></a>
    </div>
    <ul class="head-nav l">
      <li><a href="#" class="focus">系统</a><i></i></li>
      <li><a href="#">字典</a><i></i></li>
      <li><a href="#">链接</a><i></i></li>
      <li><a href="#">广告</a><i></i></li>
      <li><a href="#">资讯</a><i></i></li>
      <li><a href="#">会员</a><i></i></li>
      <li><a href="#">服务</a><i></i></li>
      <li><a href="#">店铺</a><i></i></li>
      <li><a href="#">商品</a><i></i></li>
      <li><a href="#">活动</a><i></i></li>
      <li><a href="#">订单</a><i></i></li>
      <li><a href="#">财务</a><i></i></li>
      <li><a href="#">模板</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less">
    @import './Header.less';
    @import '../../../styles/icon.less';
</style>
<!--@import '../styles/icon.less';-->