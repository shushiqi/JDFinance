<template>
  <Panel title="生活服务" :class="$style.panel">
    <section :class="$style.content">
      <ul :class="$style.content">
        <li :class="$style.item">
          <img
            src="//img12.360buyimg.com/jrpmobile/jfs/t4375/104/1184122472/3976/89741da4/58be8a6eNf10193d0.png"
            alt
          />
          <p>惠加油</p>
        </li>
        <li :class="$style.item">
          <img
            src="//img12.360buyimg.com/jrpmobile/jfs/t4747/185/1901740991/5892/1383fb93/58f57851N17ee6993.jpg"
            alt
          />
          <p>小白信用</p>
          <p>全新升级</p>
        </li>
        <li :class="$style.item">
          <img
            src="//img12.360buyimg.com/jrpmobile/jfs/t3241/234/8044685271/3713/7b29f77f/58be89c8Nb9d41295.png"
            alt
          />
          <p>信用卡还款</p>
        </li>
        <li :class="$style.item">
          <img
            src="//img12.360buyimg.com/jrpmobile/jfs/t3172/259/7993557249/4351/fd082707/58be8a81Nd7716a06.png"
            alt
          />
          <p>卡转让</p>
        </li>
        <li :class="$style.item">
          <img
            src="//img12.360buyimg.com/jrpmobile/jfs/t3085/320/8107659086/4344/cdbba2dd/58be8acfNdadcaf00.png"
            alt
          />
          <p>定期还款</p>
        </li>
      </ul>
    </section>
  </Panel>
</template>

<script>
import Panel from "../core/panel";
export default {
  components: {
    Panel
  }
};
</script>

<style lang="scss" module>
@import "../../css/element.scss";
.panel {
  @include panel;
  .content {
    @include flex(row);
    box-sizing: border-box;
    width: 100%;
    padding-bottom: 40px;
    .item {
      width: 20%;
      text-align: center;
      img {
        width: 90px;
        height: 90px;
      }
      p {
        font-size: 26px;
        color: #666;
        text-overflow: ellipsis;
        white-space: nowrap;
        overflow: hidden;
        margin-top: 12px;
        &:nth-child(3){
          color: #FF801A
        }
      }
    }
  }
}
</style>
