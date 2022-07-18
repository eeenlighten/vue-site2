<template>
    <section id="cardType" class="card__wrap section" v-bind:class="fonts">
        <h2>스킬UP 교육</h2>
        <p>국가 대표 최고의 강사진<br />우수한 교수진들의 높은 교육 완성도를 자랑합니다.</p>
        <div class="card__inner container">
            <article class="card">
                <figure class="card__header">
                    <img class="img" src="../assets/img/card01.jpg" alt="이미지1" />
                </figure>
                <div class="card__body card_color01">
                    <h3 class="title">행동교정</h3>
                    <a class="btn" href="/">더 자세히 보기</a>
                </div>
            </article>
            <article class="card">
                <figure class="card__header ">
                    <img class="img" src="../assets/img/card02.jpg" alt="이미지2"/>
                </figure>
                <div class="card__body card_color02">
                    <h3 class="title">펫푸드</h3>
                    <a class="btn" href="/">더 자세히 보기</a>
                </div>
            </article>
            <article class="card">
                <figure class="card__header">
                    <img class="img" src="../assets/img/card03.jpg" alt="이미지3" />
                </figure>
                <div class="card__body card_color03">
                    <h3 class="title">펫미용</h3>
                    <a class="btn" href="/">더 자세히 보기</a>
                </div>
            </article>
        </div>
    </section>    
</template>

<style scoped>
#cardType {
    height: 945px;
    background: #ffffff;
  }
  
  #cardType > h2 {
    font-size: 50px;
    font-weight: 500;
    text-align: center;
  }
  
  #cardType > p {
    font-size: 22px;
    font-weight: 300;
    margin: 40px;
    text-align: center;
  }
  /* card_inner */
  .card__inner {
    display: flex;
    width: 1160px;
    margin: 0 auto;
  }
  /* card_header */
  .card__header img {
    width: 376px;
    height: 525px;
  }
  /* card */
  .card {
    margin: 30px auto;
    padding-top: 80px;
  }
  /* card_body */
  .card__body {
    padding: 27px;
    text-align: center;
    position: relative;
    top: -100px;
  }
  /* color */
  .card_color01 {
    background-color: #9bb3d7;
    opacity: 0.7;
  }
  .card_color01 a {
    text-decoration: underline;
    display: inline-block;
  }
  .card_color02 {
    background-color: #cdeeff;
    opacity: 0.7;
  }
  .card_color03 {
    background-color: #ffd7d7;
    opacity: 0.7;
  }
  /* title */
  .card__body .title {
    font-size: 24px;
    font-weight: 800;
    color: #103b31;
    line-height: 1.2;
  }
  /* btn */
  .card__body .btn {
    color: #103b31;
    font-size: 14px;
  }
</style>