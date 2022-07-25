<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Card1 from './components/Card1.vue'

</script>

<template>
  <container class="flex flex-col h-full w-full overflow-hidden">
    <div class="flex flex-col h-1/2 items-center content-center space-y-4 overflow-y-auto">
      <Card1 />
      <Card1 />
      <Card1 />
    </div>

  </container>

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
