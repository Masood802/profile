<script setup>
import NavBar from "../components/NavBar.vue";
</script>
<template>
  <nav-bar></nav-bar>
  <div>
    <h1 class="text-6xl font-bold text-slate-700 text-left mt-10 mb-16 mx-16">
      My Work
    </h1>
    <div class="w-[75%] h-auto my-10 mx-auto flex justify-between items-center">
      <div
        class="w-1/3 h-96 border border-gray-500 shoadow-md mx-3 flex flex-col justify-start items-center hover:border-pink-400"
      >
        <i class="fas fa-link text-5xl text-slate-700 my-10"></i>
        <h1 class="text-slate-500">
          <span class="text-2xl font-bold text-pink-500"> Mobile UX</span>
        </h1>
        <p class="text-sm mx-5 my-5 text-center">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident
          optio doloribus doloremque necessitatibus voluptatem, tenetur eveniet
          alias cupiditate consequuntur delectus.
        </p>
      </div>
      <div
        class="w-1/3 h-96 border border-gray-500 shoadow-md mx-3 flex flex-col justify-start items-center hover:border-pink-400"
      >
        <i class="fas fa-bolt text-5xl text-slate-700 my-10 rotate-[10deg]"></i>
        <h1 class="text-slate-500">
          <span class="text-2xl font-bold text-pink-500"> WEB DESIGN</span>
        </h1>
        <p class="text-sm mx-5 my-5 text-center">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident
          optio doloribus doloremque necessitatibus voluptatem, tenetur eveniet
          alias cupiditate consequuntur delectus.
        </p>
      </div>
      <div
        class="w-1/3 h-96 border border-gray-500 shoadow-md mx-3 flex flex-col justify-start items-center hover:border-pink-400"
      >
        <i class="fas fa-tachometer-alt text-5xl text-slate-700 my-10"></i>
        <h1 class="text-slate-500">
          <span class="text-2xl font-bold text-pink-500"> HTML TEMPLATES</span>
        </h1>
        <p class="text-sm mx-5 my-5 text-center">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident
          optio doloribus doloremque necessitatibus voluptatem, tenetur eveniet
          alias cupiditate consequuntur delectus.
        </p>
      </div>
    </div>
  </div>
</template>
