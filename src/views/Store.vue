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
          title: '[주말특가]그루트 스투키 화분세트 가격:23,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1553567374465_KpbCbNXl.jpg/360/360',
          text: '영화 <가디언즈 오브 갤럭시>에 나오는 캐릭터인 귀여움으로 사랑받고있는그루투와 포름 알데히드 등 공기 중의 유해 성분을 제거해주는 실내 공기정화 식물 중의 하나인 스투키를 세트로 구매해보세요!'
        },
        {
          title: '[주말특가]편리한 선풍기 가격: 19,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557729174495_pxx0b1z.jpg/360/360',
          text: '강력한 모터,고강도 날개 누구나 사용가능한 선풍기.더운 여름 선풍기를 통해 시원하게 보내보세요!'
        },
        {
          title: '[주말특가]LED 무소음 시계 가격:14,700원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1500106063921_A.jpg/360/360',
          text : '느낌있는 시계를 소개합니다. 낮에는 반짝이는 포인트 시계로 밤에는 분위기있는 무드등 처럼 사용가능한 LED 시계입니다. 조용한 무소음시계로 학교,사무실,취침실 등 조용한 공간에서 사용하시기에 좋습니다.'
        },
        {
          title: '제습제 520ml X 24입 가격:16,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1556079461505_WEjt8YkOC.jpg/360/360',
          text : '습기로 꿉꿉하고 눅눅해진 옷과 신발,곰팡이까지 생겨 쾨쾨한 악취까지 한번에 해결! 습기의 영혼까지 완벽하게 끌어 담았습니다. 깔끔한 디자인으로 마음까지 보송보송해지세요!'
    
        },
        {
          title: '모아 미니 제습기 가격:48,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1548300305839_ZB5Y6haIDp.jpg/360/360',
          text:'저온 온도 감지 기능 내장으로 사계절 내내 사용가능.수위 감지센서로 만수시 자동 전원 OFF기능펠티어 방식으로 발열 없이 습기제거반도체 기술로 화확성분으로부터 안전하게매일 24시간 틀어도 한달 전기요금 1,130원!!'
        },
        {
          title: '에어프라이 팟 가격:13,800원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557993472866_DqguXH.jpg/360/360',
          text:'열풍이 순환 되도록 과학적으로 설계! 안전한 주방용 내열 실리콘 사용! 조리후 간편하게 꺼내는 손잡이! 간편한 세척/식기세척기 사용가능!'

        },
        {
          title: '[주말특가] 골드 글라스 no.3 가격:9,800원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557906895085_uK6gH8.jpg/360/360',
          text:'300ml 용량24K gold 수작업으로 둘러져 있습니다. 투명한 유리제품이라 어디에도 잘 어울립니다.'
        },
        {
          title: '공기정화식물+해초라탄 바구니 세트 가격:25,800원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1554300001935_vDwd4EuCbv.jpg/360/360',
          text:'공기정화능력도 좋으며 인기있는 반려식물들을 골라서 해초바구니와 매치해보았습니다. 원하는 아이를 골라 해초바구니와 함께 식물 인테리어를 연출해보세요!'
        },
        {
          title: '논슬립 바지길이&옷걸이 모음전 가격:1,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557219558378_MGU755j.jpg/360/360',
          text:'옷의 손상이나 자국없이 깔끔한 수납 가능, 다양한 컬러로 집안 분위기에 맞춰보세요!!'
        },
        {
          title: '튤립 가지 조화 1p 5colors 가격:1,260원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1519056250_105249_1.jpg/360/360',
          text:'생화같은 느낌의 컬러가 살아있는 튤립 조화, 유니크한 소프트한 느낌의 소재로꽃과 잎의 질감이 내츄럴하게 표현된 퀄리티 좋은 제품, 봄에 어울리는 사랑스러운 튤립으로 탐스럽고 화사한 분위기를 연출해보세요!!'
        },
        {
          title: '주말 욕심 정리용품 10종 가격:2,100원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1543225639716_MI2w.jpg/360/360',
          text:'깔끔하고 간편한 설치주방, 욕실 정리용품 10종을 소개합니다. 여러분의 주방과 욕실을 꾸며보세요!!'
        },
        {
          title: '레트로 스텐 케틀 ZL-18CP 가격:27,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1548913004749_pw.jpg/360/360',
          text:'친금한 바디라인,빈티지한 색감의 컬러 조합, 프랑스 감성을 느낄 수 있는 디자인 바로 여러분의 주방을 위해 태어났습니다.'
        },
        {
          title: '마리벨 면기 4colors 가격:7,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1532677342_101253_1.jpg/360/360',
          text:'진정성있는 디자인과 합리적인 가격으로 실생활에 녹아드는 식기를 만들었습니다. 가장 일상적이고 평범한 곳에 아름다움을 주입해보세요!!'
        },
        {
          title: '10장 럭스리브 호텔 수건 가격:17,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1557465631534_J3jd.jpg/360/360',
          text:'올빠짐 적은 타월, 먼지가 적은 타월, 물 빠짐이 없는 타월, 꼼꼼한 디테일 마감, 최고급 30수 마감당장 사용해보세요!!'
        },
        {
          title: '우드 티스폰 외 롱스푼 모음 가격:1,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1547442215255_3.jpg/360/360',
          text:'대추나무로 만든 우드 시리즈 나무라는 소재에서 오는 자연스러움이 음식과 함께 세팅했을때 돋보입니다. 단단한 대추나무 소재에 천연 옻칠을 한 제품으로 금수저는 아니지만 밥맛은 꿀맛이랍니다.'
        },
        
        {
          title: '규조토 욕실용품 모음전 가격:2,000원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1511229097544_dQAYB3B.jpg/360/360',
          text:'흡수성이 뛰어난 자연소재 규조토 식물성 플랑크톤이 쌓여 형성되어 지층에서 재취되는 흙 이 좋은 흙으로 만듬 욕실용품을 사용해보세요!!'
        },
        {
          title: '[1+1]홈파티&혼술 시원한 맥주잔 가격:2,500원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1555921753694_jBPLQc3cN.jpg/360/360',
          text:'혼맥하거 치맥을 할때 사용할 맥주컵이 없다구요? 지금 당장 구매하세요 취향에 따라 다양한 잔이 있습니다!!'
        },
        {
          title: '모던 화분 모음 실내공기정화 식물14종 가격: 9,900원',
          img: 'https://image.ohou.se/image/central_crop/bucketplace-v2-development/uploads-productions-1554802522_100485_1.jpg/360/360',
          text:'공기정화 식물 중에서도 실내 오염물질로 꼽히는 휘발성 유기화합물을 제거함, 미세먼지 정화,실내 습도 조절등의 역할을 하는 식물을 모던 화분에 보관해보세요!!'
        },

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