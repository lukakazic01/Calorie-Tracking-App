<template>
  <div class="container mt-5">
    <div class="row mx-0">
      <div class="col-12 d-flex justify-content-between align-items-center px-0">
       <h3 class="m-0">My food entries</h3>
       <button class="btn btn-danger" @click="openModal()">new food entry</button>
      </div>
    </div>
    <DatePicker></DatePicker>
    <CalorieTable></CalorieTable>
    <FoodEntryModal v-if="isOpened"></FoodEntryModal>
  </div>
</template>

<script>
export default{
    data() {
      return {
        isOpened:false
      }
    },
    methods: {
      openModal(){
        this.isOpened = true;
        
      }
    }
}
</script>

<style scoped>

</style>