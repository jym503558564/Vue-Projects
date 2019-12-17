<template>
  <div id="app">
    <tab-bar>
      <tabbar-item>
        <div slot="item-icon" class="iconfont icon-shouye"></div>
        <div slot="item-text">首页</div>
      </tabbar-item>
      <tabbar-item>
        <div slot="item-icon" class="iconfont icon-fenlei"></div>
        <div slot="item-text">分类</div>
      </tabbar-item>
      <tabbar-item>
        <div slot="item-icon" class="iconfont icon-gouwuche"></div>
        <div slot="item-text">购物车</div>
      </tabbar-item>
      <tabbar-item>
        <div slot="item-icon" class="iconfont icon-wode"></div>
        <div slot="item-text">我的</div>
      </tabbar-item>
    </tab-bar>
  </div>
</template>

<script>
  import TabBar from './components/tabbar/Tabbar'
  import TabbarItem from "./components/tabbar/TabbarItem";

export default {
  name: 'App',
  components: {
    TabBar,
    TabbarItem
  }
}
</script>

<style>
  @import "assets/css/base.css";
</style>