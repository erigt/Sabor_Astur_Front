<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Recipes from './components/HelloWorld.vue'
import Home from './components/Home.vue';
</script>

<template>
  <header>


    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/secction">Secction</RouterLink>
        <RouterLink to="/recipes">Recipes</RouterLink>
        
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
