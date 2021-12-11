<template>
  <div>
    <header>
      <div class="logo">
        <img src="/images/logo.svg" alt="">
      </div>
      <div class="search"></div>
      <ul class="menu">
        <li>О нас</li>
        <li>Города</li>
        <li>Контакты</li>
      </ul>
      <div class="auth_block">
        <a href="">Создать аккаунт</a>
        <a href="">Войти</a>
      </div>
    </header>
    <Nuxt />
  </div>
</template>
<template>
  <div>
    <TheHeader />
    <TheFooter />
  </div>
</template>
<script>
import TheHeader from '../components/TheHeader.vue'
import TheFooter from '../components/TheFooter.vue'
export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>
