<template>
  <div class="page">
    <div class="weui-btn-area">
      <button class="weui-btn" type="default" @click="openToast">成功提示</button>
      <button class="weui-btn" type="default" @click="openLoading">加载中提示</button>
    </div>
  </div>
</template>

<script>
import base64 from '../../../static/images/base64';
export default {
  data() {
    return {
    }
  },
  methods: {
    openToast() {
      wx.showToast({
        title: '已完成',
        icon: 'success',
        duration: 3000,
        mask: true
      });
    },
    openLoading() {
      wx.showToast({
        title: '数据加载中',
        icon: 'loading',
        duration: 3000,
        mask: true
      });
    }
  }
}
</script>

<style>
page {
  margin-top: 50px;
  padding: 15px;
  box-sizing: border-box;
}
</style>

