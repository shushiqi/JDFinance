<template>
  <Panel title="轮播图" :class="$style.panel">
    <section :class="$style.content">
      <Slider :items="items" :cname="$style.slider" />
    </section>
  </Panel>
</template>

<script>
import Panel from "../core/panel.vue";
import Slider from "../core/slider.vue";
export default {
  components: {
    Panel,
    Slider
  },
  data(){
    return{
      items:[
      {
        href: "home",
        src: '//img12.360buyimg.com/jrpmobile/jfs/t1/31588/6/14705/52443/5cbeb2b2Ea0648bba/e05f04db25d47126.png'
      },
      {
        href: "home",
        src: '//img12.360buyimg.com/jrpmobile/jfs/t1/38925/1/7734/32802/5cef91cfE8962dc90/08a7df363c6465f2.png'
      }]
    }
  }
};
</script>
<style lang="scss" module>
@import "../../css/element.scss";
.panel {
  @include panel;
  >h4{
    display: none;
  }
  .content {
    .slider {
      margin-top: 120px;
    }
  }
}
</style>