<template>
  <div class="section">
      <Navbar/>
      第5页
      <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './Navbar'
import Footer from './Footer'

export default {
  name:"Five",
  components:{ Navbar,Footer}
}
</script>