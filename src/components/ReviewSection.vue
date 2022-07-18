<template>
    <section id="reviewType" v-bind:class="fonts">
        <h2>수업 후기</h2>
        <p>수강생들의 솔직한 후기를 보실 수 있습니다.</p>
        <div class="review__inner container">
            <div class="review__box">
                <div class="desc">
                    20, 30대를 함께 보낸 아이와 이별 후 사실 죄책감이 없진 않았어요. 강의 듣고 제가 아이에게 최선을 다했다는 위로. 아직 아이 유골을 데리고 있는데 이것 또한 왠지 잘못하는 것 같은 생각을 가지고 있었고, 아이를 보내줄 수 있는 시간은 정해진것이 아니기에 준비되면 보내도 되는구나라는 조언을 처음듣고 위안이 되었습니다. 감사합니다. 
                </div>
                <div class="title">
                    <span><img class="img" src="../assets/img/smile1.png" alt="이미지1" /></span>
                    <p>이태용<span>&nbsp;펫아카데미 5기</span></p>
                    <div class="star">
                        <figure>
                        <img class="img" src="../assets/img/star.png" alt="이미지2" />
                        </figure>
                    </div>
                </div>
                <a href="/" class="btn">
                자세히보기
                </a>
            </div>
            <div class="review__box">
                <div class="desc">
                    반려견에게 집에서 간단히 어렵지 않게 만들 수 있는 간식 레시피가 다양해서 손 쉽게 만들 수 있는 수업을 듣게 되어 유익한 시간(수업)이 었습니다! 계속 만들 수 있는 수업이 이어질 수 있도록 했으면 좋겠습니다~
                </div>
                <div class="title">
                    <span><img class="img" src="../assets/img/smile2.png" alt="이미지3" /></span>
                    <p>김희진<span>&nbsp;펫아카데미 17기</span></p>
                    <div class="star">
                        <figure>
                        <img class="img" src="../assets/img/star.png" alt="이미지4" />
                        </figure>
                    </div>
                </div>
                <a href="/" class="btn">
                자세히보기
                </a>
            </div>
            <div class="review__box">
                <div class="desc">
                    너무 모르고 광범위 했던 교육이라 생각했는데 조금이나마 알 수 있었고 더 공부를 해야겠다고 생각이 들었습니다. 이론과 실습을 함께 할 수 있어 좋았고 교육하시는 교수님들도 쉽게 설명해 주셔서 좋았습니다.
                </div>
                <div class="title">
                    <span><img class="img" src="../assets/img/smile3.png" alt="이미지5" /></span>
                    <p>정승연<span>&nbsp;펫아카데미 5기</span></p>
                    <div class="star">
                        <figure>
                        <img class="img" src="../assets/img/star.png" alt="이미지6" />
                        </figure>
                    </div>
                </div>
                <a href="/" class="btn">
                자세히보기
                </a>
            </div>
        </div>
    </section>    
</template>

<style scoped>
#reviewType {

  height: 842px;
  background-color: #F6F8FD;
  padding-top: 120px;
}

#reviewType > h2 {
  font-size: 50px;
  font-weight: 500;
  text-align: center;
}

#reviewType > p {
  font-size: 22px;
  font-weight: 500;
  margin: 40px 0 80px 0;
  text-align: center;
  color: #000;
}
#reviewType .desc {
  text-align: justify; 
  line-height: 1.4;
  font-family: 'NexonLv1Gothic';
  font-weight: 500;
  overflow: hidden;
  height: 160px;
}
/* review_inner */
#reviewType .review__inner {
  display: flex;
  justify-content: space-between;
  width: 1160px;
  margin: 0 auto;
}
/* review_box */
.review__inner .review__box {
  width: 32%;
  height: 470px;
  background: #fff;
  border-radius: 15px;  
}
/* title */
.review__box .title {
  width: 313px;
  height: 112px;
  border-top: 1px solid #ddd;
  border-bottom: 1px solid #ddd;  
  margin: 20px auto;
  padding-top: 30px; 

}
.review__box .title p {
  display: inline;
  font-size: 26px;
  font-weight: 400;
  margin-left: 10px; 
}
.review__box .title p span {
  font-size: 16px;
  font-weight: 300;
}
.review__box .title span img {
  width: 55px;
  height: 55px;
  margin-top: 3px;
}
.review__box .title .star {
  position: relative;
}
.review__box .title .star img {
  width: 91px;
  height: 13px;
  position: absolute;
  top: -22px;
  left: 0;
  padding-left: 65px;
}
.review__box .desc {
  padding: 30px;
}
/* btn */
.review__box .btn {
  color: #fff;
  background: #f2d096;
  border-radius: 20px;
  text-align: center;
  display: block;
  width: 100px;
  padding: 5px 10px;
  margin: 20px auto;
  transition: 0.5s;
}
.review__box .btn:hover {
  background-color: white;
  color: #f2d096;
  border: 1px solid #f2d096;
  transition: 0.5s;
}
</style>