<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Card1 from './components/Card1.vue'

</script>

<template>
  <div class="container flex flex-col h-screen items-center justify-center overflow-y-hidden ">
    <div class="artboard phone-3 flex h-full flex-col items-center justify-center space-y-4 overflow-y-scroll">
      <Card1 />
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
