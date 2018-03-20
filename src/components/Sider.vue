<template>
  <div class="sider">
      <div class="dots">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
      </div>
      <div class="line"></div>
      <div class="num">01/05</div>
      <div class="direct">
          <div><i class="fa fa-angle-up"></i></div>
          <div><i class="fa fa-angle-down"></i></div>
      </div>
  </div>
</template>

<script>
export default {
  name:'Sider',
}
</script>

<style scoped>
    .sider{
        width: 50px;
        height: 700px;
        position: fixed;
        right: 5px;
        bottom: 25px;
    }
    .dots span{
    width: 5px;
    height: 5px;
    border: 1px solid #ddd;
    background-color: #ddd;
    margin: 10px;
    display: block;
    border-radius: 50%;
    }
    .line{
    width: 2px;
    height: 140px;
    background-color: #ddd;
    position: absolute;
    right: 35px;
    }
    .num{
        font-size: 14px;
        color: #666;
        position: absolute;
        bottom: 430px;
    }
    .direct{
    position: absolute;
    bottom: 320px;
    right: 15px;
    }
    .direct>div{
    width: 35px;
    height: 35px;
    border-radius: 50%;
    text-align: center;
    line-height: 35px;
    }
    .direct>div:nth-child(1){
        background-color: #198bfe;
    }
    .direct>div:last-child{
        margin-top: 10px;
        background-color: #ddd;
    }
    .fa.fa-angle-up,.fa.fa-angle-down{
        font-size: 30px;
        color:#fff;
    }
    
</style>


