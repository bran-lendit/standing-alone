<template>
  <div id="main-new-product">
    <p>오늘의 신상품</p>
    <main-new-product-item></main-new-product-item>
  </div>
</template>
<script>
import MainNewProductItem from './MainNewProductItem.vue'
export default {
  components: {
    MainNewProductItem
  }
}
</script>

<style lang="scss">
  #main-new-product {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-bottom: 36px;
    > p {
      font-size: 20px;
      font-weight: bold;
    }
  }
</style>
