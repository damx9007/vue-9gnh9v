<template>
  <div id="app">
    <NaviTop />
    <div class="wrapper">
      <LeftMenu />
      <Layout />
    </div>
  </div>
</template>

<script>
import NaviTop from './components/Layout.vue';
import Layout from './components/Layout.vue';
import LeftMenu from './components/Layout.vue';

export default {
  name: 'App',
  components: {
    Layout,
    NaviTop,
    LeftMenu,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
}
</style>
