<template>
<div class ="bg-black w-full ">
<navbar/>
<screen-page/>
<Footer/>

</div>
 

   




</template>

<script>
import Footer from './components/home/footer.vue'
import Navbar from './components/home/navbar.vue'
import ScreenPage from './components/home/ScreenPage.vue'












export default {
  components: {Navbar, ScreenPage, Footer  },
  name: 'App',
  
}
</script>

