<template>
  <div id="app">
    <el-row>
      <el-col :span="10">
        <span>账户：</span>
        <el-input id="name" ></el-input>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="10">
        <el-col :span="8">
        <span>密码：</span>
      </el-col>
        <el-col :span="8">
        <el-input id="password"></el-input>
      </el-col>
      </el-col>
    </el-row>
  </div>
</template>

<script>
    export default {
        name: "Login"
    }
</script>

<style scoped>

</style>
