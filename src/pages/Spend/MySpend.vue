<template>
  <div>
    <div>총 소비금액</div>
    <div>
      <span>123,456,789원</span>
      <span>아래로 화살표</span>
      <button>분석</button>
    </div>
    <div>
      쇼핑에 제일 많이 썼어요
    </div>
    <div v-for="i in 3" :key="i">
      <img src="" alt="신한패밀리카드">
      <div>
        <p>신한패밀리HI-POINT</p>
      </div>
      <div>
        1,104,254원
      </div>
    </div>
    <div>
      <p>총 수입금액</p>
      <span>화살표</span>
    </div>
  </div>
  <div>
    <div>
      <p>전체 내역</p>
      <p>달력 접기</p>
    </div>
    
  </div>
  <div>
    매달 나가는 돈
  </div>
  <div>
    보험
  </div>
  <div>
    할부
  </div>
  <div>
    <div>
      <button>-</button>
      <span>고정지출 아닌 내역 삭제</span>
    </div>
    <div>
      <button>+</button>
      <span>빠진 고정지출 추가</span>
    </div>
  </div>
</template>

<script>

export default {

}
</script>

<style>

</style>