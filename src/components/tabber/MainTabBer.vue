<template>
  <div id="app">
    <router-view></router-view>
    <tab-ber>
      <tab-ber-item path="/home" activeColor="blue">
        <img slot="item-icon" src="~assets/imgs/tabbar/home.svg" alt="">
        <img slot="item-icon-active" src="~assets/imgs/tabbar/home_active.svg" alt="">
        <div slot="item-text">首页</div>
      </tab-ber-item>
      <tab-ber-item path="/category" activeColor="green">
        <img slot="item-icon" src="~assets/imgs/tabbar/category.svg" alt="">
        <img slot="item-icon-active" src="~assets/imgs/tabbar/category_active.svg" alt="">
        <div slot="item-text">分类</div>
      </tab-ber-item>
      <tab-ber-item path="/cart" activeColor="pink">
        <img slot="item-icon" src="~assets/imgs/tabbar/cart.svg" alt="">
        <img slot="item-icon-active" src="~assets/imgs/tabbar/cart_active.svg" alt="">
        <div slot="item-text">购物车</div>
      </tab-ber-item>
      <tab-ber-item path="/profile" activeColor="red">
        <img slot="item-icon" src="~assets/imgs/tabbar/profile.svg" alt="">
        <img slot="item-icon-active" src="~assets/imgs/tabbar/profile_active.svg" alt="">
        <div slot="item-text">我的</div>
      </tab-ber-item>
    </tab-ber>
  </div>
</template>

<script>
  import TabBer from "./TabBer";
  import TabBerItem from "./TabBerItem";
  export default {
    name: "MainTabBer",
    components: {
      TabBer,TabBerItem
    }
  }
</script>

<style scoped>

</style>
