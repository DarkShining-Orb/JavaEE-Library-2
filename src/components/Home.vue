<template>
    <div>
        <h1>我是测试版首页</h1>
        <el-radio v-model="radio" label="1">备选项</el-radio>
    </div>
</template>

<script>
  export default {
    name: 'Home',
    data () {
      return {
        radio: '1'
      };
    }
  }
</script>