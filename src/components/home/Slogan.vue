<template>
<div>
  <el-card class="box-card">
    <div style="font-size: 45px;color: azure;white-space: nowrap">Talk is nothing, show you my code.</div>
    <a href="https://github.com/Antabot/White-Jotter" target="_black">
      <img src="../../assets/img/icon/icon6.png" alt="" class="git-link">
    </a>
    <a href="https://blog.csdn.net/Neuf_Soleil" target="_black">
      <img src="../../assets/img/icon/csdn.png" alt="" class="csdn-link">
    </a>
  </el-card>
</div>
</template>

<script>
export default {
  name: 'Slogan'
}
</script>

<style scoped>
  .box-card{
    width: 100%;
    height: 150px;
    background-color: #222222;
    text-align: center;
    margin-top: 5px;
  }
  .git-link{
    width: 80px;
  }
  .csdn-link {
    width: 65px;
    margin-bottom: 7px;
    margin-left: 20px;
  }
</style>
