<template>
    <section id="imageType" v-bind:class="fonts">
      <h2>현장스케치</h2>
      <p>펫 아카데미 전용 훈련장에서 현장 실습을 하고 있습니다</p>
      <div class="imageType__inner container">
          <article class="imageType__sketch">
              <figure class="sketch__header">
                  <img class="img" src="../assets/img/sketch01.jpg" alt="이미지1" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치1</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지2" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch02.jpg" alt="이미지3" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치2</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지4" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch03.jpg" alt="이미지5" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치3</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지6" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch04.jpg" alt="이미지7" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치4</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지8" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch05.jpg" alt="이미지9" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치5</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지10" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch06.jpg" alt="이미지11" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치6</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지12" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch07.jpg" alt="이미지13" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치7</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지14" />
                  </a>
              </div>
          </article>
          <article class="imageType__sketch">
              <figure class="sketch__header">
              <img class="img" src="../assets/img/sketch08.jpg" alt="이미지15" />
              </figure>
              <div class="sketch__body">
                  <h3 class="title">현장스케치8</h3>
                  <p class="desc">현장 학습 보러가기</p>
                  <a href="/" class="btn">
                    <img class="img" src="../assets/img/yellowarrow.png" alt="이미지16" />
                  </a>
              </div>
          </article>
      </div>
    </section>    
</template>

<style scoped>
#imageType {
    padding: 20px;
    background-color:#F6F8FD;
    height: 1050px;
    padding-top:150px;
}
#imageType > h2 {
    font-size: 50px;
    font-weight: 500;
    text-align: center;
  }
  #imageType > p {
    font-size: 22px;
    font-weight: 300;
    margin: 40px;
    text-align: center;
  }
  /* imageType_inner */
  .imageType__inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    text-align: center;
    width: 1160px;
    margin: 20px auto;    
  }
  /* imageType_sketch */
  .imageType__sketch {
    height: 337px;
    width: 24%;
  }
  /* sketch_header */
  .sketch__header {
    text-align: left;
    margin-bottom: 10px;
  }
  .sketch__header img {
    width: 100%;
    height: 203px;
    border-radius: 10px;
  }
  /* sketch_body */
  .sketch__body {
    text-align: left;
    position: relative;
  }
  .sketch__body .title {
    margin-bottom: 10px;
  }
  .sketch__body .desc {
    color: #555;
    font-size: 14px;
  }
  /* btn */
  .sketch__body .btn {
    position: absolute;
    top: 0;
    right: 0;
  }
  .sketch__body .btn img {
    width: 25px;
    height: 25px;
  }
</style>