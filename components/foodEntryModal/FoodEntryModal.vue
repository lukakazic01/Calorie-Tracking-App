<template>
  <div class="modal d-block bg-black bg-opacity-25" tabindex="-1" role="dialog">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">New Food Entry:</h5>
        <i class="bi bi-x-lg"></i>
      </div>
      <div class="modal-body d-flex flex-column">
        <label>Name:</label>
        <input class="mb-3">
        <label>Time:</label>
        <input class="mb-3">
        <label>Calorie value:</label>
        <input class="mb-3">
        <label>Price:</label>
        <input>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>