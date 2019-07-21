<template lang="html">
    <div>
      <iHeader></iHeader>
      <Slider></Slider>
      <Welfare></Welfare>
      <Service></Service>
      <Footer></Footer>
      <Navbar></Navbar>
    </div>
</template>

<script>
import iHeader from "../public/header";
import Slider from "./borrowSlider";
import Footer from "../public/footer";
import Navbar from "../public/navbar";
import Welfare from './welfare'
import Service from './service'
export default {
  components: {
    iHeader,
    Slider,
    Footer,
    Navbar,
    Welfare,
    Service
  }
};
</script>

<style lang="scss" >

</style>
