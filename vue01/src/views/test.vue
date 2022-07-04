<template>
  <div class="edit" style="padding: 0;margin: 0;">
    <el-container>
      <el-header>Header</el-header>
      <el-main>
        <div id="all">
          <div id="inputArea">
            <textarea dir="auto" placeholder="请输入文章内容" style="height: 300px;width: 600px;background-color: #DCDBDF"></textarea>

          </div>
          <div id="arrowArea">

          </div>
          <div id="buttonArea">
            <el-row><el-button type="primary" plain>主要按钮</el-button></el-row>
            <el-row><el-button type="success" plain>成功按钮</el-button></el-row>
          </div>
        </div>
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>


<script>
export default {
  name: 'test',
  data () {
    return {
      input: '',
    }
  },
}
</script>

<style>

textarea{
  resize:none;
}

</style>