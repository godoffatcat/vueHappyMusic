<template>
    <div class="title">
        <div class="titleFont">
            元气音乐库
        </div>
      <a-button type="primary" on:click="jumptoDownload">下载app</a-button>
    </div>
  </template>

  <script>
      export default {
        name:'TitleBar',
        methods: {
        jumptoDownload: function() {
            this.$router.push('/about')
        }
      }
      }

  </script>

  <style>
      .title {
        background: palevioletred;
        height: 70px;
        position: relative;
}
  </style>