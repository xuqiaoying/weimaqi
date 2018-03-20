<template>
  <div class="footer">
    <div class="line"></div>
    <p>Copyright@广州扬盛计算机软件 版权所有 粤ICP备15073043号</p>
  </div>
</template>

<script>
export default {
  name:'Footer',
}
</script>

<style scoped>
  .footer{
    position: absolute;
    bottom: 32px;
    left: 37px;
  }
  .line{
    width: 44px;
    height: 3px;
    background-color: #198bfe;
    margin-bottom: 10px;
  }
  .footer p{
    font-size: 14px;
  }
</style>


