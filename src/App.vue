<template>
  <div id="app">
    <div class="contains">
      <div class="dowebok"> 
         <!-- contain -->
        <First></First>
        <Second></Second>
        <Three></Three>
        <Four></Four>
        <Five></Five>
      </div>
      <Sider></Sider>
    </div>
    <!-- <router-view/> -->
  </div>
</template>

<script>
import First from './components/First'
import Sider from './components/Sider'
import Second from './components/Second'
import Three from './components/Three'
import Four from './components/Four'
import Five from './components/Five'

export default {
  name: 'App',
  components: { First,Sider,Second,Three,Four,Five}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
html,body{
  height: 100%;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  min-width: 1240px;
  height: 100%;
  /* position: relative; */
}
ul {
  list-style-type: none;
}
.contains{
  height: 100%;
}
.dowebok{
  height: 100%;
  /* overflow: hidden; */
}
.dowebok>div{
    position: relative;
    height: 100%;
}
@media (max-width: 1240px){
  #app {
    min-width: 1000px;
    height: 100%;
  }
}

</style>
