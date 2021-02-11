<template>
  <div id="app">
    <!-- 路由渲染 -->
    <keep-alive exclude="Detail">
      <router-view/>
    </keep-alive>

    <!-- 底部导航栏 -->
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
// 导入导航标签栏
import MainTabBar from 'components/content/mainTabbar/MainTabBar'

export default {
  name: 'App',
  components: {
    MainTabBar
  }
}
</script>

<style>
  /* 导入统一样式css */
  @import './assets/css/base.css';


</style>
