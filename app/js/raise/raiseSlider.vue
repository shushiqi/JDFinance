<template >
  <Panel title="金融头条" :class="$style.panel">
    <section :class="$style.content">
      <swiper :options="options">
        <swiper-slide>hashimoto</swiper-slide>
        <swiper-slide>kanna</swiper-slide>
      </swiper>
    </section>
  </Panel>
</template>

<script>
import Panel from "../core/panel";
import { swiper, swiperSlide } from "vue-awesome-swiper";
export default {
  components: {
    Panel,
    swiper,
    swiperSlide
  },
  data() {
    return {
      options: {
        autoplay: true,
        loop: true,
        direction: "vertical"
      }
    };
  }
};
</script>

<style lang="scss">
  .swiper-container-vertical{
    height: 72px;
  }
</style>


<style lang="scss" module>
@import "../../css/element.scss";
.panel {
  @include panel;
  > h4 {
    display: none;
  }
  margin-top: 120px !important;
  .content {
    height: 72px;
    line-height: 72px;
    overflow: hidden;
  }
}
</style>
