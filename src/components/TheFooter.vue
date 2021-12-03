<template>
  <header class="footer">
    <div class="container">
      <div class="footer__inner">
        <div class="footer__logo">
          <Logo></Logo>
        </div>

   
        <div class="terms-use"><a href="" class="terms-use">Условия использования</a></div>
       <div class="сopyright">
         <a href="" class="сopyright__link">Авторские права</a>
       </div>
       <div class="social-icons">
         <ul class="social-icons__list">
           <li class="social-icons__item">
             <a href="">
               
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
.footer {
background-color: var(--bac-fon);
		// .footer__inner

		&__inner {
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
