<template>
  <div id="header">
    <header class="fixed flex flex-row py-3 top-0 left-0 w-full bg-white bg-opacity-90">
      <nav class="flex justify-center w-full text-base">
        <router-link to="/" 
        class="pl-3 pr-3 hover:text-black-400 link" >ABOUT</router-link> 
        <router-link to="/Projects"
         class="pl-3 pr-3 hover:text-black-400 link">PROJECTS</router-link> 
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
  isActive: 'about'

}
</script>

<style scoped>
.link{
  font-weight: 700;
padding:10px ;
}
 
 .router-link-exact-active{
font-weight: 700;
background-color: #DDD6FE;
padding:10px ;
}



</style>