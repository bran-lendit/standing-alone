<template>
<<<<<<< HEAD
  <div class="Main">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<template>
  <div class="Main">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
=======
  <div class="home">
    <main-header/>
>>>>>>> 5d2ad5caba817b27054f01cf83f75b8ccaf7886b
  </div>
</template>

<script>
// @ is an alias to /src
import MainHeader from '@/components/MainHeader.vue'

export default {
  name: 'Main',
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

