<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Card1 from './components/Card1.vue'

</script>

<template>
  <div class="container h-1/3 flex flex-col overflow-y-auto">

    <div class="flex flex-col w-full h-100 min-h-1/2 overflow-y-auto ">
      <Card1 />
      <Card1 />
    </div>
  </div>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
