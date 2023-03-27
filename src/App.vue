<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

     <div class="container">

      <ul class="text-right">
        <li> <RouterLink to="/" >Home</RouterLink></li>
        <li> <RouterLink to="/service" >Service</RouterLink></li>
        <li><RouterLink to="/about"  >About</RouterLink></li>
        <li><RouterLink to="/portfolio" >Portfolio</RouterLink></li>
        <li><RouterLink to="/contact" >Contact</RouterLink></li>
 
      </ul>
     </div>

       
   
  </header>

  <RouterView />
  
</template>
<style lang="scss">
  header{
    background-color: black;
    color: #fff;
    overflow: hidden;
    height: 74px;
    padding: 20px;

  }
  a{
    text-decoration:none !important;
    color: #fff !important;
  }
  ul{
    padding: 5px;
    float: left;
    width: calc(100% );
    text-align: center;
  }
  li{
    display: inline;
    padding: 20px;
  }
</style>


