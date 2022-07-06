<template>
  <el-carousel indicator-position="outside">
    <el-carousel-item>
      <el-image
        style="width: 100px; height: 100px"
        src="../../assets/bg1.jpeg"
        :fit="fit"
      />
    </el-carousel-item>
    <el-carousel-item>
      <el-image
        style="width: 100px; height: 100px"
        src="../../assets/bg2.jpeg"
        :fit="fit"
      />
    </el-carousel-item>
  </el-carousel>
</template>
<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Menu from "@/components/Menu.vue"; // @ is an alias to /src

@Options({
  components: {
    Menu,
  },
})
export default class Home extends Vue {}
</script>