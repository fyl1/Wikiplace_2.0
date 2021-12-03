<template>
 <header class="header">
     <div class="container">
         <div class="header__inner">
             <div class="header__logo">
                 <Logo></Logo>
             </div>
         </div>
     </div>
 </header>

</template>
<script>

import Logo from './Logo.vue'
export default {
     components: {
    Logo
  }
}
</script>



<style lang="scss" scoped>
header{
    background: red
}
</style>
