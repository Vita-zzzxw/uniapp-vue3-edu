<template>
  <view class="content">
    <view class=""> 123 </view>
  </view>
</template>

<script setup lang="ts">
const current = ref<number>(0);

const swiperList = ref([
  "https://registry.npmmirror.com/wot-design-uni-assets/*/files/redpanda.jpg",
  "https://registry.npmmirror.com/wot-design-uni-assets/*/files/capybara.jpg",
  "https://registry.npmmirror.com/wot-design-uni-assets/*/files/panda.jpg",
  "https://registry.npmmirror.com/wot-design-uni-assets/*/files/moon.jpg",
  "https://registry.npmmirror.com/wot-design-uni-assets/*/files/meng.jpg",
]);

function handleClick(e: Event) {
  console.log(e);
}
function onChange(e: Event) {
  console.log(e);
}
</script>

<style lang="scss">
.content {
  background: #eee;
}
</style>
