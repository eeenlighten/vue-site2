<template>
    <header id="headerType" v-bind:class="fonts">
        <div class="header__inner">
            <h1 class="header__logo">
                <a href="/">PET ACADEMY</a>
            </h1>
            <nav class="header__menu">
                <h2 class="ir_so">메인 메뉴</h2>
                <ul>
                    <li><a href="/">아카데미소개</a></li>
                    <li><a href="/">전문교육과정</a></li>
                    <li><a href="/">취창업정보</a></li>
                    <li><a href="/">수강후기</a></li>
                    <li><a href="/">고객센터</a></li>
                </ul>
            </nav>
        </div>
    </header>    
</template>

<style scoped>
#headerType {
    height: 200px;
    background-color: #fff;
  }
  /* header_inner */
.header__inner {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  /* header_logo */
  .header__logo {
    margin-top: 48px;
    flex: 5;
    color: #103b31;
  }
  /* header_menu */
  .header__menu {
    flex: 5;
  }
  .header__menu ul li {
    display: inline-block;
    padding: 5px 20px;
  }
  .header__menu ul li a {
    font-weight: 400;
    padding: 10px;
    transition: background 0.3s;
  }
  .header__menu ul li a:hover {
    background: #f2d096;
    color: #fff;
    border-radius: 5px;
  }
  
</style>