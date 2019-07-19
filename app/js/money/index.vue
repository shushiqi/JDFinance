<template lang="html">
    <div>
      <iHeader></iHeader>
      <!-- <Slider></Slider> -->
      <Footer></Footer>
      <Navbar></Navbar>
    </div>
</template>

<script>
import iHeader from "../public/header";
// import Slider from './moneySlider'
import Footer from '../public/footer'
import Navbar from '../public/navbar'
export default {
  components: {
    iHeader,
    // Slider,
    Footer,
    Navbar
  }
};
</script>

<style lang="scss" >

</style>
