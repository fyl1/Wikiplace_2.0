<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header__logo">
          <Logo></Logo>
        </div>

        <div class="search">
          <input type="text" class="search__input"  placeholder="Найдите место"/>
        </div>
        <div class="menu">
          <ul class="menu__list">
            <li class="menu__item">
              <a href="">О нас</a>
            </li>
            <li class="menu__item"><a href="">Города</a></li>
            <li class="menu__item"><a href="">Контакты</a></li>
          </ul>
        </div>
        <div class="create-account">
          <a href="" class="create-account__link"></a>
        </div>
        <div class="enter">
          <a href="" class="enter__link"></a>
        </div>
      </div>
    </div>
  </header>
</template>
<script>
import Logo from "./Logo.vue";
export default {
  components: {
    Logo,
  },
};
</script>

<style lang="scss" scoped>
header {
  background: red;
}
</style>
