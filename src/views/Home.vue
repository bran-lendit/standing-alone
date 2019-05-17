<template>
  <div class="Main">
    <main-header/>
    <main-new-product></main-new-product>
    <main-today-food></main-today-food>
  </div>
</template>

<script>
// @ is an alias to /src
import MainHeader from '@/components/MainHeader.vue'
import MainNewProduct from '../components/MainNewProduct.vue'
import MainTodayFood from '../components/MainTodayFood.vue'
export default {
  name: 'Main',
  components: {
    MainHeader,
    MainNewProduct,
    MainTodayFood
  }
}
</script>
<style lang="scss">
  .home {
    max-width: 1000px;
    margin: 0 auto;
  }
</style>

