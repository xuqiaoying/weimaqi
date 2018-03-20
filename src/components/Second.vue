<template>
  <div class="section">
      <Navbar/>
      <div class="main">
          <div class="left">
              <p>#Administration</p>
              <h1>营收监控界面</h1>
              <ul>
                  <li v-for="(list,index) in lists" :key="index"><div>{{list.icon}}{{list.adm}}</div></li>
              </ul>
              <div>MORE+</div>
          </div>
      </div>
      <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './Navbar'
import Footer from './Footer'

export default {
  name:"Second",
  components:{ Navbar,Footer},
  data(){
      return{
          lists:[
              {icon:'1',adm:'基本设置'},
              {icon:'2',adm:'子账号管理'},
              {icon:'3',adm:'提现管理'},
              {icon:'4',adm:'订单管理'},
              {icon:'5',adm:'设备管理'},
              {icon:'6',adm:'吸粉机管理'},
              {icon:'7',adm:'商品管理'},
              {icon:'8',adm:'统计管理'},
              {icon:'9',adm:'会员管理'},
              {icon:'10',adm:'清单管理'},
              {icon:'11',adm:'库存管理'},
              {icon:'12',adm:'商家推广'},
          ]
      }
  }
}
</script>

<style scoped>
    .main{
    width: 80%;
    border: 1px solid #ccc;
    margin-left: auto;
    margin-right: auto;
    margin-top: 350px;
    }
</style>

