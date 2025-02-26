<template>
   <section class="relative w-screen flex items-center justify-center h-[calc(100vh-3.5rem)]">
      <div class="w-[calc(100%-12px)] max-w-[1200px] flex gap-5">
         <div class="flex-1 flex flex-col justify-center">
            <h1 class="text-5xl font-bold mb-5">Ola! Eu sou <span class="relative before:h-2 before:w-full before:content-['ola_as'] before:absolute before:bg-blue-500 before:bottom-0 before:text-transparent before:overflow-hidden">Faelson</span> <span>Nunes</span>.</h1>
            <p class="text-base">Fala, dev_! Eu sou Faelson09, um simples nerd aficionado por programação, tecnologia e tudo que envolve o mundo digital. Desde cedo, mergulhei no universo do código e, ao longo do tempo, fui aprimorando minhas habilidades em diversas linguagens e frameworks.</p>
         </div>
         <div class="flex-1 flex flex-col justify-center h-full">
            <NuxtImg src="https://i.postimg.cc/NjNsMC0J/download20250105161631.png" class="h-full"/>
         </div>
      </div>
   </section>
   <!-- {{ ola }} -->
   <!-- <button v-on:click="clickando()" class="bg-red-500 w-fit h-fit px-5 py-2 rounded text-white">clique aqui!</button> -->
</template>
   
   <script>
   export default {
      data() {
         return {
            ola: "mmmmmm"
         }
      }
   }
   </script>
   
   <!-- 
   <style>
   div.s {
      width: 100vw;
      height: 100vh;
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
   }
   </style> -->
   