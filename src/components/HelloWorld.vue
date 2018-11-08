<template>
  <div class="hello">
    <el-row>
      <el-col :span="24">
        <div class="d1">AAA</div>
      </el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :span="10">
        <div class="d1">BBB</div>
      </el-col>
      <el-col :span="14">
        <div class="d1">CCC</div>
      </el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :span="6" :offset="6">
        <div class="d1">DDD</div>
      </el-col>
      <el-col :span="6" :offset="4">
        <div class="d1">EEE</div>
      </el-col>
    </el-row>
    <el-row :gutter="20" type="flex" justify="space-around">
      <el-col :span="4">
        <div class="d1">DDD</div>
      </el-col>
      <el-col :span="4">
        <div class="d1">EEE</div>
      </el-col>
      <el-col :span="4">
        <div class="d1">DDD</div>
      </el-col>
      <el-col :span="4">
        <div class="d1">EEE</div>
      </el-col>
    </el-row>
    <el-container>
      <el-header>Header</el-header>
      <el-main>Main</el-main>
      <el-footer>Footer</el-footer>
    </el-container>
    <br><br>
    <el-container>
      <el-header>Header</el-header>
      <el-container>
        <el-aside>Aside</el-aside>
        <el-main>Main</el-main>
      </el-container>
      <el-footer>Footer</el-footer>
    </el-container>
    <br><br>
    <i class="el-icon-success"></i>
    <br>
    <el-button type="primary" icon="el-icon-error">错误</el-button>
    <el-button>按钮<i class="el-icon-success el-icon--right"></i></el-button>
    <br>
    <el-button type="primary" :loading="true">加载中</el-button>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.d1{
  color:white;
  background-color:blue;
  margin:10px 0;
}
.el-header,.el-main,.el-footer,.el-aside{
  border:2px solid black;
}
</style>
