<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink> -->

<template>

  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">Content</RouterLink>
  </nav>
 
   <p class="time"><HelloWorld /></p>
   <RouterView />


</template>

<style scoped>

nav a.router-link-exact-active {
  color: #CBE4DE;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display:inline-block;
  padding: 0 1rem;
  border-left: 1px;
}

</style>
