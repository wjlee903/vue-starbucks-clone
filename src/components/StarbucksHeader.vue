<template>
  <header>
    <!-- logo ----------------------------------------------------------------->
    <div class="logo">
      <img
        src="https://www.starbucks.co.kr/common/img/common/logo.png"
        alt="logo"
      />
    </div>
    <!-- logo -->

    <!-- NavBar ----------------------------------------------------------------->
    <div class="nav_wrap">
      <nav class="serviceNav">
        <ul class="serviceItems">
          <li class="serviceItem"><a href="#">Sign In</a></li>
          <li class="serviceItem"><a href="#">My Starbucks</a></li>
          <li class="serviceItem">
            <a href="#">Customer Service & Ideas</a>
          </li>
          <li class="serviceItem"><a href="#">Find Store</a></li>
          <li class="serviceItem">
            <input type="text" placeholder="검색어를 입력하세요" />
          </li>
          <li class="serviceItem">
            <button>
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </li>
        </ul>
      </nav>
      <nav class="menuNav">
        <ul class="menuItems">
          <li class="menuItem">
            <a href="#">COFFEE</a>
            <div>
              <ul class="menuSubItems">
                <li><a href="#">커피</a></li>
                <li><a href="#">스타벅스 원두</a></li>
                <li><a href="#">스타벅스 비아</a></li>
                <li><a href="#">스타벅스앳홈 by 캡슐</a></li>
              </ul>
              <ul class="menuSubItems">
                <li><a href="#">나와 어울리는 커피</a></li>
              </ul>
              <ul class="menuSubItems">
                <li><a href="#">스타벅스 리저브™</a></li>
                <li><a href="#">RESERVE MAGAZINE</a></li>
              </ul>
              <ul class="menuSubItems">
                <li><a href="#">에스프레소 음료</a></li>
                <li><a href="#">도피오</a></li>
                <li><a href="#">에스프레소 마키아또</a></li>
                <li><a href="#">아메리카노</a></li>
                <li><a href="#">마키아또</a></li>
                <li><a href="#">카푸치노</a></li>
                <li><a href="#">라떼</a></li>
                <li><a href="#">모카</a></li>
              </ul>
              <ul class="menuSubItems">
                <li><a href="#">커피를 즐기는 법</a></li>
                <li><a href="#">커피 프레스</a></li>
                <li><a href="#">푸어 오버</a></li>
                <li><a href="#">아이스 푸어 오버</a></li>
                <li><a href="#">커피 메이커</a></li>
                <li>
                  <a href="#">리저브를 매장에서 다양하게 즐기는 법</a>
                </li>
              </ul>
              <ul class="menuSubItems">
                <li><a href="#">커피 이야기</a></li>
                <li><a href="#">농장에서 우리의 손으로</a></li>
                <li><a href="#">최상의 아라비카 원두</a></li>
                <li><a href="#">스타벅스 로스트 스펙트럼</a></li>
                <li><a href="#">스타벅스 디카페인</a></li>
                <li><a href="#">스클로버® 커피 추출 시스템</a></li>
              </ul>
            </div>
          </li>
          <li class="menuItem"><a href="#">MENU</a></li>
          <li class="menuItem"><a href="#">STORE</a></li>
          <li class="menuItem"><a href="#">RESPONSIBILTY</a></li>
          <li class="menuItem"><a href="#">STARBUCKS REWARDS</a></li>
          <li class="menuItem"><a href="#">WHAT'S NEW</a></li>
        </ul>
      </nav>
    </div>
    <!-- NavBar -->
  </header>
</template>
<script>
export default {
  name: "StarbucksHeader",
  components: {},
  data() {
    return {};
  },
  beforeCreate() {},
  created() {},
  beforeMount() {},
  mounted() {},
  beforeUpdate() {},
  updated() {},
  beforeUnmount() {},
  unmounted() {},
  methods: {},
};
</script>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
}
html {
  font-size: 20px;
}
body {
  font-size: 1rem;
  font-family: "Source Sans Pro";
}
ul,
li {
  list-style: none;
}
a {
  text-decoration: none;
  color: inherit;
}
button {
  outline: none;
  cursor: pointer;
}
header {
  display: flex;
  align-items: center;
  width: 100%;
  padding: 1rem 4rem;
}
header .logo {
  padding: 0.8rem;
}
header > nav {
  flex-direction: column;
}
.nav_wrap {
  padding-right: 20%;
}
.serviceNav {
  display: block;
  text-align: center;
  width: 100%;
}

.serviceNav .serviceItems {
  display: flex;
  justify-content: flex-end;
  padding-right: 70px;
}
.serviceNav .serviceItems .serviceItem {
  padding: 0.5em;
  font-size: 14px;
}
.serviceItem > input {
  display: none;
}
.serviceItem button {
  font-size: 1.7em;
}
.menuNav {
  width: 100%;
}
.menuItems {
  display: flex;
}
.menuItems .menuItem {
  padding: 1em;
}
.menuItems .menuItem a {
  font-size: 16px;
}
.menuItems .menuItem .menuSubItems {
  width: 100%;
  display: none;
}
.menuItems .menuItem:hover {
  background-color: #2c2a29;
}
.menuItems .menuItem:hover a {
  color: #beb6b3;
  text-decoration-line: underline;
}
.menuItems .menuItem:hover .menuSubItems {
  display: block;
}
</style>
