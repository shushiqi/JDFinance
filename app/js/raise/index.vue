<template lang="html">
    <div>
      <iHeader></iHeader>
      <Slider></Slider>
       <Daily></Daily>    
       <In></In>
      <Footer cname="moneyFooter"></Footer>
      <Navbar></Navbar>
    </div>
</template>

<script>
import iHeader from "../public/header";
import Slider from "./raiseSlider";
import Footer from "../public/footer";
import Navbar from "../public/navbar";
import Daily from "./daily"
import In from './in'
export default {
  components: {
    iHeader,
    Slider,
    Footer,
    Navbar,
    Daily,
    In
  }
};
</script>

<style lang="scss" >
.moneyFooter {
  margin-top: 0;
  ul {
    li:first-child {
      display: none;
    }
  }
}
</style>
