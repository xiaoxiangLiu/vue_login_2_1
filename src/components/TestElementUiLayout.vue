<template>
  <el-row :gutter="20">
    <el-col :span="6">
      <div class="el-icon-s-grid">
      <el-button type="text">第一列文字按钮</el-button>
        <el-button type="primary">主要按钮</el-button>
      </div>
    </el-col>
    <el-col :span="6">
      <el-button>第二列文字按钮</el-button>
    </el-col>
    <el-col :span="6">
      <el-button type="text">第三列文字按钮</el-button>
    </el-col>
  </el-row>
</template>

<script>
    export default {
        name: "TestElementUiLayout"
    }
</script>

<style scoped>

</style>
