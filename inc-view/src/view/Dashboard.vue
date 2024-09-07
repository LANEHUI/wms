<template>
  <el-row class="warp">
    <el-col :span="24" class="warp-breadcrum">
      <el-breadcrumb separator="/">
        <el-breadcrumb-item :to="{ path: '/' }"><b>首页</b></el-breadcrumb-item>
      </el-breadcrumb>
    </el-col>
   <el-col :span="24" class="warp">
    <h3>welcome</h3>
    <div class="demo-image__lazy">
      <el-image  style="width: 100%; height: 100%" fit="cover" src="https://fuss10.elemecdn.com/a/3f/3302e58f9a181d2509f3dc0fa68b0jpeg.jpeg"/>
    </div>
   </el-col>
    
  </el-row>

</template>

<script lang="ts" setup>

</script>

<style scoped>
.demo-image__lazy {
  height: 550px;
  overflow-y: auto;
}
</style>
