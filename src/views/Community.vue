<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div v-for="img in list.img" :key="img">
      <img :src="img" alt="" width="30" height="30">
    </div>
  </div>
</template>

<script>
export default {
  name: 'community',
  data () {
    return {
      list: {
        img: [
          "https://d224jl0o7z9gbn.cloudfront.net/uploads/advices/cover_images/medium_1453688454520_ZXtnt3sMq.JPG",
          "https://d224jl0o7z9gbn.cloudfront.net/uploads/advices/cover_images/medium_1453688454520_ZXtnt3sMq.JPG",
        ]
      }
    }
  }
}
</script>

<style lang="scss">

</style>
