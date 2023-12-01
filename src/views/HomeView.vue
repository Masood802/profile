<script setup>
import { useRouter } from 'vue-router';
let router = useRouter();
</script>
<template>
 
  <div
    style="background-image: url('public/home-bg.jpg')"
    class="w-full bg-cover flex flex-col justify-center items-center h-screen bg-fixed"
  >
    <h1 class="text-3xl uppercase font-bold text-orange-600 mb-2 mt-32">
      Masood Ur Rehman
    </h1>
    <h3 class="text-xl uppercase font-semibold text-cyan-700 mb-2">
      FROntEnd Developer
    </h3>
    <p class="w-[60%] text-center text-sm">
      I am professional <span class="font-semibold">UI Desinger</span> and
      <span class="font-semibold">Front-End Developer</span> creating modern and
      responsive designs for <span class="font-semibold">Web</span> and
      <span class="font-semibold">Mobile.</span> Let us work togather.Thank you.
    </p>
    <button  @click="router.push('/my-work')" class="px-3 py-2 bg-cyan-600 w-40 my-3 rounded text-slate-200">
      Let's Begin
    </button>
  </div>
</template>

