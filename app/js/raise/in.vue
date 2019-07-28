<template lang="html">
    <Panel title="in货推荐" :class="$style.panel">
        <section :class="$style.content">
          <div :class="$style.item">
            <img />
            <section :class="$style.list">
              <div></div>
            </section>
          </div>
        </section>
    </Panel>
</template>

<script>
import Panel from "../core/panel.vue"
export default {
    components: {
        Panel,
    },
    data(){
      items:[
        {
          img: '',
          text1: '',
          text2: ''
        }
      ]
    }
}
</script>

<style lang="scss" module>
  @import "../../css/element.scss";
  .panel{
    @include panel;
    .content{
      @include flex(row);
    }
  }
</style>
