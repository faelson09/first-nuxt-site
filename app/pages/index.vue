<template>
   {{ ola }}
   <button v-on:click="clickando()" class="bg-red-500 w-fit h-fit px-5 py-2 rounded text-white">clique aqui!</button>
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
   