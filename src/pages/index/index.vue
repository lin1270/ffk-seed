<template>
  <div id="app">
    <div class="aaa">gg</div>
    <div class="bbb">gg</div>
    <div class="testimg"> </div>
  </div>
</template>

<script>

export default {
  name: 'Index',
  mounted() {
  },
};
</script>

<style lang="less">
@import "./index.less";

.testimg {
  position: absolute;
  background: url(~@/img/logo.png);
  width: 100px;
  height: 100px;
  background-size: 100% 100%;
  z-index: 10000;
}
</style>
