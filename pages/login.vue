<template>
<div class="container">
  <div class="row justify-content-center">
    <div class="col-12 d-flex flex-column login-container">
      <div class="w-100 text-center mt-5">
        <p>Login</p>
      </div>
      <label class="mb-2">Username:</label>
      <input placeholder="Username">
      <label class="mb-2 mt-2">Password:</label>
      <input placeholder="Password">
      <button class="btn btn-danger mt-3">Log in</button>
    </div>
  </div>
</div>
</template>

<script setup lang="ts">

</script>

<style scoped>
@import "../assets/login.css";
</style>