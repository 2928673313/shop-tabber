<template>
  <div id="app">
    <main-tab-ber/>
  </div>
</template>

<script>
const MainTabBer = () => import('./components/tabber/MainTabBer')
export default {
  name: 'App',
  components: {
    MainTabBer
  }
}
</script>

<style>
@import "./assets/css/base.css";

</style>
