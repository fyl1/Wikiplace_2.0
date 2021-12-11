<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header__logo">
          <Logo></Logo>
        </div>

        <div class="search">
          <input
            type="text"
            class="search__input"
            placeholder="Найдите место"
          />
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

<style lang="scss">
@import "../assets/scss/base/variables.scss";
.header {
  // .header__inner

  &__inner {
    display: flex;
    justify-content: space-between;
    padding: 30px 0;
  }

  // .header__logo

  &__logo {
  }
}

.search {
  // .search__input

  &__input {
    width: 100%;
    max-width: 257px;
    border-radius: 20px;
    padding: 5px 20px 5px;

    font-size: 16px;
    font-family: $m-fons;
    font-weight: 400;
    color: $tex-bec;
    line-height: 1.6;
  }
}
.menu {
  // .menu__list

  &__list {
    display: flex;
  }

  // .menu__item

  &__item {
    margin-right: 40px;
    font-size: 16px;
    font-family: $m-fons;
    color: $main-text;
    line-height: 1.6;
    font-weight: normal;
  }
}
.create-account {
  // .create-account__link

  &__link {
  }
}
.enter {
  // .enter__link

  &__link {
  }
}
</style>
