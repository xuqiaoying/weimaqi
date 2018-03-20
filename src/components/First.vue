<template>
  <div class="section">
      <Navbar/>
      <div class="content">
          <h1>黑科技维码器</h1>
          <p>支持多个平台<span>|</span>安装简易功能强大<span></span>后台实时把控数据</p>
          <div>立即购买</div>
      </div>
      <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './Navbar'
import Footer from './Footer'

export default {
  name:"First",
  components:{ Navbar,Footer}
}
</script>

 <style scoped>
 .content{
    width: 500px;
    height: 500px;
    border: 1px solid #ddd;
    margin: 0 auto;
    margin-top: 180px;
    text-align: center;
    position: relative;
 }
 .content p{
    bottom: 90px;
    position: absolute;
    left: 72px;
 }
 .content div{
     position: absolute;
    bottom: 30px;
    left: 185px;
    width: 130px;
    height: 35px;
    line-height: 35px;
    border: 1px solid #ccc;
    border-radius: 17px;
    font-size: 14px;
    background: -webkit-linear-gradient(left top, #35a4FE,#106bff); /* Safari 5.1 - 6.0 */
    background: -o-linear-gradient(bottom right, #35a4FE, #106bff); /* Opera 11.1 - 12.0 */
    background: -moz-linear-gradient(bottom right, #35a4FE, #106bff); /* Firefox 3.6 - 15 */
    background: linear-gradient(to bottom right, #35a4FE , #106bff); /* 标准的语法 */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#35a4FE', endColorstr='#106bff',GradientType=0 ); 
 }
 :root .content div{filter:none;}

     /* .first{
         background: url(../assets/1.jpg) no-repeat fixed;
         background: #999;
    } */
 </style>


