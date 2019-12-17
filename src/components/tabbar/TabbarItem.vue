<template>
  <div class="tab-bar-item" @click="itemClick">
    <slot name="item-icon"></slot>
    <slot name="item-text"></slot>
  </div>
</template>

<script>
  export default {
    name: "TabbarItem",
    props:{
      path: String,
    },
    methods: {
      itemClick(){
        this.$router.push(this.path)
      },
    }
  }
</script>

<style scoped>
  @import "./../../assets/css/iconfont.css";
  .tab-bar-item {
    flex: 1;
    text-align: center;
    height: 49px;
  }
</style>