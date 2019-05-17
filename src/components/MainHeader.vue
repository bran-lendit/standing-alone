<template>
  <div id="main-header">
      <div class="story-entry-container">
          <div>
            <p>가볍게</p>
            <p>맛있게</p>
            <p>먹고싶을때</p>
          </div>
      </div>
      <el-carousel >
        <el-carousel-item v-for="item in 3" :key="item">
        </el-carousel-item>
      </el-carousel>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  #main-header {
    display: flex;
    .story-entry-container {
      max-width: 75%;
      min-height: 1px;
      box-sizing: border-box;
      padding-bottom: 28%;
      flex: 0 0 75%;
      background-image: url('https://mp-seoul-image-production-s3.mangoplate.com/web/resources/bndai-bcgf7x2rtb.jpg?fit=around|*:*&crop=*:*;*,*&output-format=jpg&output-quality=80');      background-size: cover;
      background-repeat: no-repeat;
      border-radius: 12px;
      margin-right: 8px;
      > div {
        > p {
          position: relative;
          top: 0;
          text-align: left;
          color: white;
          font-size: 32px;
          margin: 0;
          padding-left: 24px;
          font-weight: 700;
          &:nth-child(1) {
            margin-top: 24px;
          }
        }
      }
    }
    .el-carousel {
      min-width: 25%;
    }
    .el-carousel__item {
      background-image: url('https://image.ohou.se/image/resize/bucketplace-v2-development/uploads-banners-home_banner-1554259177802_RBKJ.jpg/850/none');
      background-size: cover;
      padding-bottom: 53%;
      border-radius: 12px;
    }
  }
</style>
