<template>

  <div class="store">
    
    <div v-for="(item,index) in items" :key="index">
      <store-item :item="item"></store-item>
    </div>
    <store-item></store-item>
    
    
  </div>
  
</template>
<script>
import StoreItem from '../components/StoreItem.vue'
export default {
  components: {
    StoreItem
  },
  data() {
    return {
      items: [
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1553567374465_KpbCbNXl.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557729174495_pxx0b1z.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1552474510756_l3FF.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1553567374465_KpbCbNXl.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557729174495_pxx0b1z.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1552474510756_l3FF.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1553567374465_KpbCbNXl.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557729174495_pxx0b1z.jpg/360/360'
        },
        {
          title: '상품에 대하여 설명하겠습니다.',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1552474510756_l3FF.jpg/360/360'
        }

      ]
    }
  }
}
</script>

<style lang="scss" scoped>
.store {
  max-width: 1000px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
   div {
	  display: flex;
	  justify-content: center; 
	  justify-content: space-around;
    flex-wrap: wrap;
    // min-width: 900px;
    
  }
}

</style>
