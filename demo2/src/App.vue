<template>
  <el-container>
    <el-header><Menu></Menu></el-header>
    <el-main>

      <router-view></router-view>
    </el-main>
    <el-footer>
      <Footer></Footer>
    </el-footer>
  </el-container>
</template>

<script>
import Menu from "./components/Menu.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Menu,
    Footer,
  },
};
</script>

<style>
#app {
  margin: 0;
  padding: 0;
}
body {
  padding: 0px;
  margin: 0px;
}
a {
  text-decoration: none;
}
.el-main{
  height: calc(100vh - 360px) !important;
}
.el-header {
  --el-header-padding: 0px !important;
}
.el-footer {
  --el-footer-padding: 0px !important;
}
</style>
