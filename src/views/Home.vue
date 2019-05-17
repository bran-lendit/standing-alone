<template>
  <div class="home">
    <main-header/>
    <main-new-product></main-new-product>
  </div>
</template>

<script>
// @ is an alias to /src
import MainHeader from '@/components/MainHeader.vue'
import MainNewProduct from '../components/MainNewProduct.vue'
export default {
  name: 'home',
  components: {
    MainHeader,
    MainNewProduct
  }
}
</script>
<style lang="scss">
  .home {
    max-width: 1000px;
    margin: 0 auto;
  }
</style>

