<template>
  <div class="section">
      <Navbar/>
      第3页
      <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './Navbar'
import Footer from './Footer'

export default {
  name:"Three",
  components:{ Navbar,Footer}
}
</script>