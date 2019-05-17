<template>
  <div id="main-new-product-item">
    <div v-for="(item, index) in list" :key="index">
      <img :src="item.img" alt="" width="220" height="220">
    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {
      list: [
        {
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-exhibitions-cover_image-1557827165574_Suio.jpg/640/426',
          title: '[희망일배송] 론다 3인용 워셔블 패브릭 소파베드',
          salePercent: '60%',
          price: '24,000원'
        },
        {
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-exhibitions-cover_image-1557983244840_I0.jpg/640/426',
          title: '뉴 디퓨저 1종',
          salePercent: '40%',
          price: '20,000원'
        },
        {
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1533262788001_5pgXlLmTr.jpg/425/425',
          title: '심플 식기세트',
          salePercent: '10%',
          price: '10,500원'
        },
        {
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1515485172_100004_1.jpg/425/425',
          title: '아일랜드 식탁',
          salePercent: '5%',
          price: '50,500원'
        }
      ]
    }
  }
}
</script>

<style lang="scss">
  #main-new-product-item {
    display: flex;
    flex-wrap: wrap;
    > div {
      display: flex;
      > img {
        margin-right: 16px;
        border-radius: 8px;
      }
    }

  }
</style>
