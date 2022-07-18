<template>
    <section id="bannerType" class="banner__wrap section" v-bind:class="fonts">
        <h2 class="ir_so">배너 영역</h2>
        <div class="banner__inner">
            <h3 class="banner__title">PET ACADEMY</h3>
            <p class="banner__desc">
                취업과 창업에 강한 PET ACADEMY<br />소수 정예 교육으로 개인 수준에 따른 맞춤형 교육을 진행합니다.
                <a href="/">바로 가기</a>
            </p>
        </div>
    </section>    
</template>

<style scoped>
#bannerType {
    height: 300px;
}
.banner__wrap {
    background-image: url(../assets/img/banner02.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
}
/* bnner_inner */
.banner__inner {
    text-align: left;
    color: #000;
    position: relative;
    width: 1160px;
    margin: 0px auto;
}
/* banner_title */
.banner__title {
    font-size: 50px;
    font-weight: 800;
    margin-bottom: 20px;
    text-align: left;
}
/* banner_desc */
.banner__desc {
    font-size: 24px;
    line-height: 1.5;
    font-weight: 300;
    margin-bottom: 70px;
}
.banner__desc a {
    display: block;
    font-size: 16px;
    line-height: 3;
    font-weight: bold;
    color: #fff;
    text-decoration: none;
    margin-top: 50px;
    width: 200px;
    text-align: center;
    background-color: #f2d096;
    transition: 0.5s;
}
.banner__desc a:hover {
    background-color: white;
    color: #f2d096;
    border: 1px solid #f2d096;
    transition: 0.5s;
}

</style>