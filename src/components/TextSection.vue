<template>
    <section id="textType"> 
        <div class="textType__wrap">
            <h2 class="ir_so"> 교육과정 </h2>    
            <div class="textType__text">                  
                <span>PET MASTER</span>
                <h2>펫마스터<br/>전문과정
                </h2>
                <p>펫마스터로 취업하기 위한 전문 과정입니다.<br/>여러분들도 도전해보세요!</p>
            </div>
            <div class="textType__inner container">
                <div class="text">
                    <h3>반려동물 관리사</h3>
                    <p>반려동물 케어 전반을 익혀 기본부터<br/>한 발 앞서나가는 만능 펫테이너의 필수 소양</p>
                </div>
                <div class="text">
                    <h3>반려동물식품관리사</h3>
                    <p>블루오션 끝.판.왕!<br/>반려동물 먹거리 산업 필수 교육 과정</p>
                </div>
                <div class="text">
                    <h3>반려동물 행동교정사</h3>
                    <p>반려동물을 잘 다루는 사람이 시장에서 성공한다! 반려동물 산업의 필수인력!</p>
                </div>
                <div class="text">
                    <h3>펫뷰티션</h3>
                    <p>반려동물 산업의 중심!<br/>위생부터 미용, 의상 제작부터 악세서리까지</p>
                </div>
            </div>
        </div>    
    </section>    
</template>

<style scoped>
#textType {

    height: 681px;
    background-color: #F6F8FD;
  }
  /* textType_wrap */
 .textType__wrap {
    display: flex;
    justify-content: space-between;
    width: 1160px;
    margin: 0px auto;
    padding-top: 150px;
  }
  /* textType_text */
  .textType__text {
    width: 30%;
  }
  .textType__text span {
    background: #f2d096;
    padding: 10px 20px;
    border-radius: 20px;
    color: #fff;
    margin-bottom: 20px;
    display: inline-block;
  }
  .textType__text h2 {
    font-size: 50px;
    font-weight: bold;
    margin-bottom: 20px;
  }
  .textType__text p {
    margin-top: 20px;
    line-height: 1.5;
    font-size: 16px;
  }
  /* textType_inner */
  .textType__inner {
    width: 70%;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin: 0px 36px;
  }
  .textType__inner .text {
    width: 45%;
    margin-bottom: 20px;
    line-height: 1.5;
    font-weight: 300;
    
  }
  .textType__inner .text h3 {
    margin-bottom: 20px;
    padding-top: 60px;
    position: relative;
  }
  .textType__inner .text h3:before {
    content: '';
    width: 50px;
    height: 50px;
    border-radius: 50%;
    position: absolute;
    left: 0;
    top: 0;
  }
  .textType__inner .text:nth-child(1) h3::before {
    background-image: url('../assets/img/texttype4.png');
    background-size: contain;
  }
  .textType__inner .text:nth-child(2) h3::before {
    background-image: url('../assets/img/texttype2.png');
    background-size: contain;
  }
  .textType__inner .text:nth-child(3) h3::before {
    background-image: url('../assets/img/texttype3.png');
    background-size: contain;
  }
  .textType__inner .text:nth-child(4) h3::before {
    background-image: url('../assets/img/texttype1.png');
    background-size: contain;
  }

  .textType__inner .text p {
    word-break: keep-all;
  }
  
</style>