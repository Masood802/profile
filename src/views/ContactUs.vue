<script setup>
import NavBar from "../components/NavBar.vue";
</script>
<template>
  <nav-bar></nav-bar>
  <div class="flex my-20 items-center justify-center">
    <span class="text-semibold text-4xl mx-2 text-gray-700">MY </span>
    <h1 class="text-4xl font-bold text-gray-700 mx-1">PORTFOLIO</h1>
  </div>
  <div class="w-1/2 mx-auto flex justify-center items-center">
    <button class="mr-1 w-auto px-5 py-2 hover:bg-cyan-700 active:bg-cyan-700">
      ALL
    </button>
    <button class="mr-1 w-auto px-5 py-2 hover:bg-cyan-700">HTML</button>
    <button class="mr-1 w-auto px-5 py-2 hover:bg-cyan-700">Photoshop</button>
    <button class="mr-1 w-auto px-5 py-2 hover:bg-cyan-700">Wordpress</button>
    <button class="mr-1 w-auto px-5 py-2 hover:bg-cyan-700">Mobile</button>
  </div>
  <div></div>
</template>
