<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-danger align-items-center justify-content-end">
      <ul class="d-flex flex-row">
        <li class="p-2 text-light"><NuxtLink to="/login" class="nuxt-link">Login</NuxtLink></li>
        <li class="p-2 text-light"><NuxtLink to="/" class="nuxt-link">Food Entries</NuxtLink></li>
      </ul>
    </nav>
  </div>
</template>

<script setup lang="ts">
 
</script>

<style scoped>
 @import "./navbar.css";
</style>