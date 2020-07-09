<template>
  <div>
      <div class="banner">
        <a-carousel autoplay>
          <div><h3>1</h3></div>
          <div><h3>2</h3></div>
          <div><h3>3</h3></div>
          <div><h3>4</h3></div>
        </a-carousel>
      </div>
  </div>
</template>
    <script>
    export default {
      name: 'Banner'
    };
    </script>
    <style scoped>
    /* For demo */
    .ant-carousel >>> .slick-slide {
      text-align: center;
      height: 160px;
      line-height: 160px;
      background: #364d79;
      overflow: hidden;
    }

    .ant-carousel >>> .slick-slide h3 {
      color: #fff;
    }
    </style>

