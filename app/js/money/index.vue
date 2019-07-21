<template lang="html">
    <div>
      <iHeader></iHeader>
      <Slider></Slider>
      <AdFirst></AdFirst>
      <Money></Money>
      <AdSecond></AdSecond> 
      <Finance></Finance>  
      <AdThird></AdThird>      
      <Footer cname="moneyFooter"></Footer>
      <Navbar></Navbar>
    </div>
</template>

<script>
import iHeader from "../public/header";
import Slider from "./moneySlider";
import Footer from "../public/footer";
import Navbar from "../public/navbar";
import AdFirst from "./adFirst";
import Money from "./money";
import AdSecond from "./adSecond";
import Finance from "./finance";
import AdThird from "./adThird";
export default {
  components: {
    iHeader,
    Slider,
    Footer,
    Navbar,
    AdFirst,
    Money,
    AdSecond,
    Finance,
    AdThird
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
