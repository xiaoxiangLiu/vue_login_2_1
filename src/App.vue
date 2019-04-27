<template>
  <div id="app">
    <el-header>这是App的header</el-header>
    <img src="./assets/logo.png">
    <Login></Login>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Login from './components/Login'
import TestElementUiLayout from './components/TestElementUiLayout'
export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
