<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const counted = ref(0)
</script>

<template>
  <div class="card w-96  bg-base-100 shadow-xl">
    <figure><img src="https://placeimg.com/400/225/arch" alt="Shoes" /></figure>
    <div class="card-body">
      <h2 class="card-title">
        Shoes!
        <div class="badge badge-secondary">NEW</div>
      </h2>
      <p class="text-secondary">If a dog chews shoes whose shoes does he choose?</p>
      <div class="card-actions justify-end">
        <div class="badge badge-outline">Fashion</div>
        <div class="badge badge-outline">Products</div>
      </div>
      <button type="button" class="btn btn-primary" @click="counted++">count is: {{ counted }}</button>

    </div>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
