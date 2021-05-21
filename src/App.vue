<template>
<div class ="bg-black w-full ">
<navbar/>
<screen-page/>
<Footer/>

</div>
 

   




</template>

<script>
import Footer from './components/footer.vue'
import Navbar from './components/navbar.vue'

import ScreenPage from './components/ScreenPage.vue'










export default {
  components: { ScreenPage, Navbar, Footer},
  name: 'App',
  
}
</script>

