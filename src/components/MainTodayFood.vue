<template>

<div>
  <div class="for-margin">
    <div class = "today-cook">
      <p>오늘의 요리</p>
    </div>
    <div class="cook-container1">
      <div class="cook" @click="clickItem(0)">
        <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/direction/image_file/57875/mid_thumb_0.JPG&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
        <div class="name">현 암</div>
        <div class="desc">매운양념만두</div>
      </div>

      <div class="cook">
        <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/recipe/image_file/4071/mid_thumb_______2.png&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
          <div class="name">현 암</div>
        <div class="desc">맥앤치즈그라탕</div>
      </div>

      <div class="cook">
        <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/recipe/image_file/3588/mid_thumb_cereal_chicken_01.png&convert=jpgmin&rt=600.jpg" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
        <div class="name">현 암</div>
        <div class="desc">단짠단짠 순살치킨</div>
      </div>

        <div class="cook">
          <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/recipe/image_file/1837/mid_thumb_main_1837.png&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
          <div class="name">현 암</div>
          <div class="desc">야끼소바빵</div>
        </div>
    </div>
    
    <div class="cook-container1">
        <div class="cook">
          <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/recipe/image_file/2417/mid_thumb_30_______.jpg&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
          <div class="name">현 암</div>
          <div class="desc">소금구이덮밥</div>
        </div>
        <div class="cook">
          <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/recipe/image_file/2292/mid_thumb_main_2292.png&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
          <div class="name">현 암</div>
          <div class="desc">허니콜팝</div>
        </div>
        <div class="cook">
          <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/recipe/image_file/1920/mid_thumb_main_1920.png&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
          <div class="name">현 암</div>
          <div class="desc">과일롤</div>
        </div>
        <div class="cook">
          <img src="https://cloudfront.haemukja.com/vh.php?url=https://d1hk7gw6lgygff.cloudfront.net/uploads/direction/image_file/13056/mid_thumb_0_m.JPG&convert=jpgmin&rt=600" width="200" height="200">
          <div class="profile">
            <img class="_6q-tv" src="https://scontent-icn1-1.cdninstagram.com/vp/c0c6ec3577f86ce0fc4f351c897676d3/5D65A9D0/t51.2885-19/s320x320/54512593_428193027933863_4489466032460660736_n.jpg?_nc_ht=scontent-icn1-1.cdninstagram.com" alt="hyun_am님의 프로필 사진">
          </div>
          <div class="name">현 암</div>
          <div class="desc">식빵치즈스틱</div>
        </div>
    </div>
  </div>
</div>

</template>


<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    clickItem (id) {
      console.log(id)
      this.$router.push(`${id}`)
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div.profile{
  img._6q-tv {
    width: 100px;
    height: 100px;
    border-radius: 150px; /* 레이어 반크기만큼 반경을 잡기*/    
    vertical-align: middle;
    text-align: center;    
    position: relative;
    bottom: 60px;
  }
}

div.name{
  opacity: 0.6;
  margin-top: -110px;
  text-align: center;
  padding: 50px;
}

div.for-margin {
  width: 850px;
  margin: auto;
}

div.today-cook {
  text-align: left;
  font-size: 25px;
  font-weight: bold;
  
}

div.cook-container1 {
  display: flex;
  
}

div.cook {
  margin: 5px;
  border: 1px solid #ccc;
  width: 200px;
  height: 300px;

}

div.cook:hover {
  border: 1px solid #777;
}

div.cook img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
  margin-top: -70px;
}

img:hover{
  opacity:0.7;
}

</style>
