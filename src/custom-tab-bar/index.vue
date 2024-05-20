<template>
  <view class="custom-tab-bar">
    <nut-row>
      <nut-col :span="24">
        <view class="content" style="background: #7d7e80">span:24</view>
      </nut-col>
      <nut-col :span="12">
        <view class="content" style="background: #fffbe8">span:12</view>
      </nut-col>
      <nut-col :span="6">
        <view class="content" style="background: #323233">span:6</view>
      </nut-col>
    </nut-row>
  </view>
</template>

<script setup>
  definePageConfig({
    component: true,
  })
</script>

<style></style>
