<template>
  <div class="head">
    <div class="header">
      <div class="header__left">
        <div class="header__left__logo">LOGO</div>
      </div>
      <div class="header__middle"></div>
        <nav class="header__middle__nav">
          <ul>
            <li>
              <a>문자발송</a>
            </li>
            <li>
              <a>주소록</a>
            </li>
            <li>
              <a>발송함</a>
            </li>
            <li>
              <a>충전소</a>
            </li>
            <li>
              <a>고객센터</a>
            </li>
          </ul>
        </nav>
      <div class="header__right">
        <div class="header__right__items">ITEM_BOX</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.head {
  width: 100%;
  display: flex;
  justify-content: center;
}
.header {
  width: 65%;
  height: 50px;
  display: flex;
  justify-content: space-between;
}
.header__left__logo {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100px;
  height: 100%;
  border: 1px solid #ccc;
  text-align: center;
}
.header__middle__nav {
  width: 80%;
  display: flex;
  align-items: center;
}
.header__middle__nav > ul {
  width: 100%;
  display: flex;
  justify-content: space-around;
}
.header__middle__nav > ul > li {
  font-size: 18px;
  font-weight: 400;
}
.header__right__items {
  width: 100px;
  height: 100%;
  border: 1px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
