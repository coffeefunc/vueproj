<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar/>
    <!-- <tab-bar>
      <tab-bar-item path='/home' activeColor="blue">
        <template v-slot:item-icon> <img src="./assets/img/tabbar/home.svg"/> </template>
        <template v-slot:item-icon-active> <img src="./assets/img/tabbar/home_active.svg"/> </template>
        <template v-slot:item-text> <div>首页</div> </template>
      </tab-bar-item>
      <tab-bar-item path='/category'>
        <template v-slot:item-icon> <img src="./assets/img/tabbar/category.svg"/> </template>
        <template v-slot:item-icon-active> <img src="./assets/img/tabbar/category_active.svg"/> </template>
        <template v-slot:item-text> <div>分类</div> </template>
      </tab-bar-item>
      <tab-bar-item path='/cart' activeColor="pink">
        <template v-slot:item-icon> <img src="./assets/img/tabbar/shopcart.svg"/> </template>
        <template v-slot:item-icon-active> <img src="./assets/img/tabbar/shopcart_active.svg"/> </template>
        <template v-slot:item-text> <div>购物车</div> </template>
      </tab-bar-item>
      <tab-bar-item path='/profile' activeColor="deepPink">
        <template v-slot:item-icon> <img src="./assets/img/tabbar/profile.svg"/> </template>
        <template v-slot:item-icon-active> <img src="./assets/img/tabbar/profile_active.svg"/> </template>
        <template v-slot:item-text> <div>我的</div> </template>
      </tab-bar-item>
    </tab-bar> -->
  </div>
</template>

// <script>
// import TabBar from './components/tabbar/TabBar'
// import TabBarItem from './components/tabbar/TabBarItem'
import MainTabBar from './components/MainTabBar'

  export default {
    name: 'App',
    components: {
        // TabBar,
        // TabBarItem
        MainTabBar
    }
  }
</script>

<style>
  @import './assets/css/base.css';
</style>
