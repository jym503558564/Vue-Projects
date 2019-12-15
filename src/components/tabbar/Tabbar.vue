<template>
  <div id="tab-bar">
    <div class="tab-bar-item">
      <div class="iconfont icon-shouye"></div>
      <div>首页</div>
    </div>
    <div class="tab-bar-item">
      <div class="iconfont icon-fenlei"></div>
      <div>分类</div>
    </div>
    <div class="tab-bar-item">
      <div class="iconfont icon-gouwuche"></div>
      <div>购物车</div>
    </div>
    <div class="tab-bar-item">
      <div class="iconfont icon-wode"></div>
      <div>我的</div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "TabBar"
  }
</script>

<style scoped>
  @import "./../../assets/css/iconfont.css";

  #tab-bar {
    display: flex;
    background-color: #f6f6f6;

    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;

    box-shadow: 0 -1px 1px rgba(100,100,100,0.1);

  }
  .tab-bar-item {
    flex: 1;
    text-align: center;
    height: 49px;
  }
</style>