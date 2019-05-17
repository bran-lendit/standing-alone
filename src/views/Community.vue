<template>
  <div class="community">
    <h2>Community</h2>
  
    <hr class="my-hr1">
    <article class="questions-item">
      <div class="questions-content-text">
        <router-link to="communitydetail">[ 거실 전면인테리어 ㅜㅜ도와주세요 ]</router-link>
        <p id="first">티비다이를 너무짧은걸 샀나봐요. 왼쪽을 어떻게 꾸밀지 고민이에요ㅠㅠ 화분을 놓고 싶기도하고 물티슈 등 수납공간이 부족하여 수납가능한 선반을 놓고싶기도한데.. 맞는컬러가 무엇일까요?? 네이비 인테리어하기 힘드네요ㅠ 더워보여요</p>

      </div>
      <div class="questions-content-img">
        <img src="https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-cards-snapshots-1558099940_tlUmVe.jpeg/320/320" width="120" height="120">
      </div>
    </article>  
    <hr class="my-hr1">

    <article class="questions-item">
      <div class="questions-content-text">
        <router-link to="communitydetail">[ 제방 가구배치를 다시하려고 하는데 도와주세요ㅠㅠ]</router-link>
        <p id="first">제가 침대와 철제선반 사이에 이케아 스탠드를 놓았는데 코드 꼿는데가 옷장있는쪽이라 선이 문제가되서 이참에 가구배치를 다시 하고싶어요.<br>어떻게 하면 좋을까요?인테리어 능력자님들 도와주세요~제발 댓글부탁드려요~~♡-♡</p>

      </div>
      <div class="image-wrap square">
        <img src="https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-cards-snapshots-1558088650_oHdHKivMI.jpeg/320/320" width="120" height="120">
      </div>
      </article>  
        <hr class="my-hr1">
        <article class="questions-item">
      <div class="questions-content-text">
        <router-link to="communitydetail">[ 작은 시골집 리모델링 ]</router-link>
        <p id="first">총 4개의 방 오른쪽 아니면 왼쪽만 1개의 방을 만들려고요<br> 나머지는 벽은 남긴체 도어를 다제거하고 마루와 같이 사용 하고요양쪽 2개 만드는것보다 괜찮을까요?크기는 왼쪽이 조금 커요</p>

      </div>
     <div class="image-wrap square">
                <img src="https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-cards-snapshots-1558079199_vhEJVch4.jpeg/320/320" width="120" height="120">
      </div>
      </article>                 
    
    <hr class="my-hr1">
    <article class="questions-item">
      <div class="questions-content-text">
        <router-link to="communitydetail">[ 주방타일과 새로들어올 식탁과 어울릴까요? ]</router-link>
        <p id="first">저희 주방타일색이 너무 어두워요 ㅠㅠ 

이제 식탁도 원목의 밝은 느낌인데 괜찮을까 모르겠어요....
(저 몰딩색비슷한 4인용식탁)

조언좀부탁드랴요 ㅠㅠㅠ
제일 큰 고민은 새로들어올 식탁하고 저 타일하고 어울릴지 같이 고민해주시면 감사하겟습니당 ㅜㅜ </p>

      </div>
      <div class="image-wrap square">
                <img src="https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-cards-snapshots-1558064830_JIDaH.jpeg/320/320" width="120" height="120">
              </div>
    </article>

        <hr class="my-hr1">
  </div>
  
</template>

<style lang="scss">

.community {
  .questions-item {
    display: flex;
    justify-content: space-between;
    .questions-content-text {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      > a {
        font-size: 18px;
        font-weight: bold;
      }
    }
    .questions-content-img {

    }
  }
}
button {
  background-color: rgb(80, 123, 163); /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
h1:hover{
  background-color: white;
  color: black;
}
h1:visited{
  text-decoration: none;
    
}
div{
    margin: 30px;
}
#first{
   
    font-size: 17px;
    padding: 10px;
    font-weight: bold;
    text-align: left;
    
} 
.my-hr1 {
    border: 0;
    height: 10px;
    background:rgb(80, 123, 163);
  }
a:link  { 
    text-decoration:none;
}

a:visited{
    color: black;
}
</style>