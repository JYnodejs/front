<template>
  <div >
     <h1>{{msg}}</h1>
     <el-button type="success" v-on:click="login" icon="el-icon-check">登录</el-button>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    login () {
      this.$message({
        message: '恭喜您登陆成功',
        type: 'success'
      })
    }
  }
}
</script>
