<template>
  <div class="section">
      <Navbar/>
      第4页
      <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './Navbar'
import Footer from './Footer'

export default {
  name:"Four",
  components:{ Navbar,Footer}
}
</script>