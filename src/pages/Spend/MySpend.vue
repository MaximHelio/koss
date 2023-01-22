<template>
  <div class="basic">
    <div style="display:felx flex:1">총 소비금액</div>
    <br>
    <div class="container">
      <div clas>
        <span>123,456,789원</span>
        <span>
          <svg style="width:24px;height:24px" viewBox="0 0 24 24">
            <path fill="currentColor" d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" />
          </svg>
        </span>
      </div>
      <button>분석</button>
    </div>
    <div>
      쇼핑에 제일 많이 썼어요
    </div>
    <div v-for="i in 3" :key="i" class="container">
      <svg style="width:10%" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><title>card-account-details</title><path d="M2,3H22C23.05,3 24,3.95 24,5V19C24,20.05 23.05,21 22,21H2C0.95,21 0,20.05 0,19V5C0,3.95 0.95,3 2,3M14,6V7H22V6H14M14,8V9H21.5L22,9V8H14M14,10V11H21V10H14M8,13.91C6,13.91 2,15 2,17V18H14V17C14,15 10,13.91 8,13.91M8,6A3,3 0 0,0 5,9A3,3 0 0,0 8,12A3,3 0 0,0 11,9A3,3 0 0,0 8,6Z" /></svg>
      <div>
        <div>
          <p>신한패밀리HI-POINT</p>
        </div>
        <div>
          1,104,254원
        </div>
      </div>
    </div>
    <br>
    <div class="container">
      <span>총 수입금액</span>
      <span>
        <svg style="width:24px;height:24px" viewBox="0 0 24 24">
          <path fill="currentColor" d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" />
        </svg>
      </span>
    </div>
  </div>
  <div>
    <div>
      <p>전체 내역</p>
      <p>달력 접기</p>
      <div>

      </div>
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
    <div class="container">
      <div>
        <svg style="width:24px;height:24px" viewBox="0 0 24 24">
          <path fill="currentColor" d="M17,13H7V11H17M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2Z" />
        </svg>
        <span>고정지출 아닌 내역 삭제</span>
      </div>
      <div>
        <svg style="width:24px;height:24px" viewBox="0 0 24 24">
          <path fill="currentColor" d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" />
        </svg>
      </div>
    </div>
    <div class="container">
      <div>
        <svg style="width:24px;height:24px" viewBox="0 0 24 24">
          <path fill="currentColor" d="M17,13H13V17H11V13H7V11H11V7H13V11H17M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2Z" />
        </svg>
        <span>빠진 고정지출 추가</span>
      </div>
      <div>
        <svg style="width:24px;height:24px" viewBox="0 0 24 24">
          <path fill="currentColor" d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" />
        </svg>
      </div>
    </div>
  </div>
</template>

<script>

export default {
 
}
</script>

<style>
.container{
  display: flex; 
  justify-content: center;
  align-content: center;
}
</style>