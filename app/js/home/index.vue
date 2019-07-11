<template lang="html">
    <div>
      <iHeader></iHeader>
      <Slider></Slider>
      <Novice></Novice>
    </div>
</template>

<script>
import iHeader from "../public/header";
import Slider from './homeSlider'
import Novice from './novice'
export default {
  components: {
    iHeader,
    Slider,
    Novice
  }
};
</script>

<style lang="scss" module>

</style>
