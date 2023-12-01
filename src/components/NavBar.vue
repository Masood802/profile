<script setup>
import { RouterLink, useRouter } from "vue-router";
let router = useRouter();
</script>

<template>
  <div class="w-full h-16 flex justify-between items-center shadow-md cursor-pointer">
    <div class="ml-3 flex items-center text-pink-500" @click="router.push('/')">
      Ultra
      <span class="text-cyan-700">Profile</span>
    </div>
    <div
      class="flex justify-center items-center w-1/2 mx-auto text-gray-800 bg-transparent h-16"
    >
      <router-link
        to="/"
        class="text-gray-800 mx-2 hover:text-pink-500 transition-all duration-75 uppercase"
      >
        Home</router-link
      >
      <router-link
        to="/my-work"
        class="text-gray-800 mx-2 hover:text-pink-500 transition-all duration-75"
      >
        MY WORK</router-link
      >
      <router-link
        to="/contact-us"
        class="text-gray-800 mx-2 hover:text-pink-500 transition-all duration-75 uppercase"
      >
        Portfolio</router-link
      >
      <router-link
        to="/contact-us"
        class="text-gray-800 mx-2 hover:text-pink-500 transition-all duration-75 uppercase"
      >
        about</router-link
      >
      <router-link
        to="/contact-us"
        class="text-gray-800 mx-2 hover:text-pink-500 transition-all duration-75 uppercase"
      >
        contact</router-link
      >
    </div>
  </div>
</template>
