<template>
  <header class="footer">
    <div class="container">
      <div class="footer__inner">
        <div class="footer__logo">
          <Logo></Logo>
        </div>

        <div class="terms-use">
          <a href="" class="terms-use">Условия использования</a>
        </div>
        <div class="сopyright">
          <a href="" class="сopyright__link">Авторские права</a>
        </div>
        <div class="social-icons">
          <ul class="social-icons__list">
            <li class="social-icons__item">
              <a href="">
                <svg src="~/assets/icons/fes.svg"></svg>
              </a>
            </li>
            <li class="social-icons__item">
              <a href="">
                <svg src="~/assets/icons/vk.svg"></svg>
              </a>
            </li>
            <li class="social-icons__item">
              <a href="">
                <svg src="~/assets/icons/odnok.svg"></svg>
              </a>
            </li>
          </ul>
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
 .footer {
    // background-color: var(--bac-fon);
    background-color: $bac-fon;
    max-height: 100px;
    // .footer__inner
  
    &__inner {
      display: flex;
      justify-content: space-between;
      padding: 20px 0;
    }
  
    // .footer__logo
  
    &__logo {
    }
  }
  .terms-use {
  }
  .сopyright {
    // .сopyright__link
  
    &__link {
    }
  }
</style>
