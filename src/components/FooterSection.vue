<template>
    <footer id="footerType" class="footer__wrap section" v-bind:class="fonts">
        <h2 class="ir_so">푸터 영역</h2>
        <div class="footer__inner container">
            <div class="footer__wrap">
                <div class="footer_left">
                    <div class="footer_info">
                        <h3>PET ACADEMY</h3>
                        <ul>
                            <li>안녕하세요!</li>
                            <li>더 다양한 정보확인</li>
                            <li>petacademy@gmail.com</li>
                        </ul>
                    </div>
                    <div class="icon">
                        <ul>
                            <li><a href="/"><img class="img" src="../assets/img/icon1.png"  alt="이미지1"/></a></li>
                            <li><a href="/"><img class="img" src="../assets/img/icon2.png"  alt="이미지2"/></a></li>
                            <li><a href="/"><img class="img" src="../assets/img/icon3.png"  alt="이미지3"/></a></li>
                            <li><a href="/"><img class="img" src="../assets/img/icon4.png"  alt="이미지4"/></a></li>   
                            <li><a href="/"><img class="img" src="../assets/img/icon5.png"  alt="이미지5"/></a></li>               
                        </ul>
                    </div>
                </div>
                <div class="footer__menu">
                    <div>
                        <h3>소개</h3>
                        <ul>
                            <li><a href="/">아카데미 소개</a></li>
                            <li><a href="/">오시는길</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3>강의안내</h3>
                        <ul>
                            <li><a href="/">개강 일정</a></li>
                            <li><a href="/">국비과정 NCS</a></li>
                            <li><a href="/">일반과정 개강</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3>컨설팅</h3>
                        <ul>
                            <li><a href="/">블랙탑 컨설팅</a></li>
                            <li><a href="/">창업센터</a></li>
                        
                        </ul>
                    </div>
                    <div>
                        <h3>커뮤니티</h3>
                        <ul>
                            <li><a href="/">현장스케치</a></li>
                            <li><a href="/">공지사항</a></li>
                            <li><a href="/">이벤트</a></li>
                            <li><a href="/">sns</a></li>
                            <li><a href="/">건의함</a></li>
                            <li><a href="/">취업지원센터</a></li>
                        </ul>
                    </div>
                </div> 
            </div>
            <address class="footer__address">
                Copyright 2022. All Rights Reserved. - Designde by JS
            </address>
        </div>
    </footer>    
</template>

<style scoped>
#footerType {
    height: 400px;

    background: #fff;
  }
  /* footer_inner */
  .footer__inner {
    width: 1160px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  /* footer_wrap */
  .footer__wrap {
    display: flex;
  }
  /* footer_left */
  .footer_left {
    width: 37%;
  }
  /* footer_info */
  .footer_info {
    text-align: left;
  }
  .footer_info h3 {
    font-size: 18px;
    font-weight: 500;
  }
  .footer_info ul {
    margin: 30px 0;
    line-height: 1.5;
    font-size: 16px;    
    color: #777;
    font-family: 'NexonLv1Gothic';
  }
  /* footer_address */
  .footer__address {
    border-top: 1px solid #ccc;
    margin-top: 50px;
    padding-top: 50px;
    color: #777;
    font-family: 'GmarketSans';
    font-weight: 300; 
  }
  /* icon */
  .icon {
    margin-left: -68px;
    margin-top:40px;
  }
  .icon li{
      padding: 15px;
      font-size: 30px;
      width: 25px;
      text-align: center;
      text-decoration: none;
      border-radius: 50%;
      background: #f5f5f5;
      color: #000000; 
      display: inline;   
  }
  .icon li:nth-child(n + 2) {
    margin-left: 11px;
  }
  .icon li:nth-child(4) img{
    width: 35px;
    padding-top: 3px;
  }
  .icon li:nth-child(5) img{
    padding-top: 8px;
  }
  .icon li img{
    width: 35px;
  }
  .footer__menu {
    display: flex;
    width: 63%;
  }
  /* footer_menu */
  .footer__menu > div {
    text-align: left;
    margin: 0 38px 0 50px;
  }
  .footer__menu > div h3 {
    font-size: 22px;
    font-weight: 500;
    margin-bottom: 20px;
  }
  .footer__menu > div li a {
    font-size: 15px;
    line-height: 1.8;
    color: #777;
    font-weight: 300;
  }
  .footer__menu > div li a:hover {
    text-decoration: underline;
  }
</style>