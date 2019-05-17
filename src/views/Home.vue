<template>
  <div class="home">
    <main-header/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainHeader from '@/components/MainHeader.vue'

export default {
  name: 'home',
  components: {
    MainHeader
  }
}
</script>
<style lang="scss">
  .home {
    max-width: 1000px;
    margin: 0 auto;
  }
</style>

