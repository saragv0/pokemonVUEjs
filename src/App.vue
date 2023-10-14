<script setup>
import { RouterLink, RouterView } from 'vue-router'



</script>

<template>
<nav class="navbar bg-body-tertiary">
  <div class="container">

      <RouterLink class="navbar-brand" to="/">
      <img src="@/assets/logo.svg" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
      Pokemons 
    </RouterLink>
    <div>
      <RouterLink type="button" class="btn btn-outline-success me-2" to="/" >Home</RouterLink>
      <RouterLink type="button" class="btn btn-outline-success" to="/pokemons" >Pokemons</RouterLink>
    </div>

   
  </div>
</nav>


<div class="container"> 
  <RouterView />

</div>

</template>


