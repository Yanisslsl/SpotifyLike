<template>
  <header class="border-b border-black md:flex md:items-center md:justify-between p-4 pb-0 shadow-lg md:pb-4   ">
  
  
  <div class="flex items-center justify-between mb-4 md:mb-0 divide-x-2 divide-green-500 text-white">
    <h1 class=" flex items-center justify-between leading-none text-2xl text-white">
      <img src='../assets/spotify.png' style="width: 50px">
      <a class=" p-2 text-grey-darkest hover:text-green-600" href="#">
        Spotify
      </a>
    </h1>

    <a class="text-black hover:text-orange md:hidden" href="#">
      <i class="fa fa-2x fa-bars"></i>
    </a>
  </div>
  <!-- END Logo text or image -->
  
  <!-- Search field -->
 
  <!-- END Search field -->
  
  <!-- Global navigation -->
  <nav class="text-white">
    <ul class=" md:flex md:items-center justify-beetween ">
      <li class="md:ml-4 px-10">
        <a class="block no-underline   text-white hover:text-green-600 md:border-none md:p-0" href="#">
          Premium
        </a>
      </li>
      <li class="md:ml-4 px-10">
        <a class="border-t block no-underline   hover:text-green-600 md:border-none md:p-0" href="#">
          Assistance
        </a>
      </li>
      <li class="md:ml-4 px-10">
        <a class="border-t block no-underline   hover:text-green-600 md:border-none md:p-0" href="#">
          Télécharger
        </a>
      </li>
    
          <div class="flex items-center">

               <img src='../assets/user.png' style="width: 50px">
<li class="md:ml-4 px-5">
 <a class="border-t block no-underline   hover:text-green-600 md:border-none md:p-0 " href="#">
          Profil
        </a>
       
      </li>
          </div>
      
    </ul>
  </nav>
  <!-- END Global navigation -->

</header>
</template>

<script>


export default {
  
  name: 'navbar'
}
</script>

