<script setup lang="ts">
import { onLaunch, onShow, onHide } from "@dcloudio/uni-app";
onLaunch(() => {
  console.log("App Launch");
});
onShow(() => {
  console.log("App Show");
});
onHide(() => {
  console.log("App Hide");
});
</script>
<style>
@import url('@kviewui/kviewui/styles/kviewui/index.css');
/* 引入动画包样式 */
@import url('@kviewui/animate/styles/index.css');
</style>
