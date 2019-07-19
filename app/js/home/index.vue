<template lang="html">
    <div>
      <iHeader></iHeader>
      <Slider></Slider>
      <Novice></Novice>
      <Borrow></Borrow>
      <Money></Money>
      <Product></Product>
      <Life></Life>
      <Footer></Footer>
      <Navbar></Navbar>
    </div>
</template>

<script>
import iHeader from "../public/header";
import Slider from './homeSlider'
import Novice from './novice'
import Borrow from './borrow'
import Money from './money'
import Product from './product'
import Life from './life'
import Footer from '../public/footer'
import Navbar from '../public/navbar'
export default {
  components: {
    iHeader,
    Slider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    Footer,
    Navbar
  }
};
</script>

<style lang="scss" >

</style>
