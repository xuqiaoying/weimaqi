<template>
    <div class="header">
    <div class="logo">
      <img src="../assets/logo.png" alt="logo">
    </div>
    <div class="nav">
      <ul>
        <li v-for="(item,index) in bars" :key="index">{{item}}</li>       
      </ul>
        <!-- <div>登录</div> -->
        <i class="fa fa-bars"></i>
    </div>
  </div>
</template>

<script>
export default {
  name:'Navbar',
  data(){
    return{
      bars:['首页','硬件产品','软件服务','合作案例','加入我们','登录']
    }
  }
}
</script>

<style scoped>

.header{
    /* position: absolute; */
    width: 94%;
    /* height: 45px; */
    margin: 0 auto;
    margin-top: 29px;
    /* line-height: 45px; */
}
.logo img{
  width:40px;
  height: 40px;
}
.nav{
    position: absolute;
    right: 0px;
    top: 0px;
    display: flex;
}
.nav ul li{
  padding: 0px 17px;
  border-right: 2px solid #cbcbcb;
  font-size: 14px;
  float: left;
  color: #cbcbcb;
}
.nav ul li span{
      padding: 21px;
}
.nav ul li:nth-child(6){
  border-right: none;
  border: 1px solid #ccc;
  text-align: center;
  width: 28px;
  height: 28px;
  line-height: 28px;
  border-radius: 14px;
  background: -webkit-linear-gradient(left top, #35a4FE,#106bff); /* Safari 5.1 - 6.0 */
  background: -o-linear-gradient(bottom right, #35a4FE, #106bff); /* Opera 11.1 - 12.0 */
  background: -moz-linear-gradient(bottom right, #35a4FE, #106bff); /* Firefox 3.6 - 15 */
  background: linear-gradient(to bottom right, #35a4FE , #106bff); /* 标准的语法 */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#35a4FE', endColorstr='#106bff',GradientType=0 ); 
  color:white;
  margin: -5px 44px 0px 15px;
}
:root .nav ul li:nth-child(6){filter:none;} 

.fa.fa-bars{
  color: #ccc;
  font-size: 23px;
  margin-right: 32px;
}
</style>


