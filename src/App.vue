<template>
  <div id="app">
    <el-card class="login-card">
      <el-form>
      <el-form-item style="margin-top: 20px">
        <el-input placeholder="请输入手机号" ></el-input>
      </el-form-item>
      <el-form-item>
        <el-input placeholder="请输入密码"></el-input>
      </el-form-item>
      <el-form-item>
        <el-button type="primary" style="width: 100%">登录</el-button>
      </el-form-item>
    </el-form>
    </el-card>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  width: 100%;
  height: 100vh;
  background-color: pink;
  display: flex;
  justify-content: center;
  align-items: center;
}
.login-card {
   width: 430px;
   height: 300px;
 }
</style>
