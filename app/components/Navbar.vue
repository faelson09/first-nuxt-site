<template>
   <header class="w-screen shadow-sm h-14 flex items-center justify-center">
      <nav class="w-[calc(100%-12px)] max-w-[1200px] flex items-center justify-between">
         <a href="" class="flex gap-2 items-center">
            <NuxtImg src="/favicon.ico"/>
            Valhalla
         </a>
         <ul class="flex items-center gap-5">
            <li v-for="(item, index) in nav" :key="index">
               <a :href="item.link" class="border-b border-b-transparent duration-300 hover:border-b-blue-500 text-base">{{ item.page }}</a>
            </li>
         </ul>
      </nav>
   </header>
</template>

<script lang="ts">
   export default {
      data() {
         return {
            nav:[
               {
                  page:"Home", 
                  link:"/"
               },
               {
                  page:"About",
                  link:"/about"
               },
               {
                  page:"Services",
                  link:"/services" 
               },
               {
                  page:"Portfolio",
                  link:"/portfolio"
               },
               {
                  page:"Blog",
                  link:"/blog"
               },
               {
                  page:"Contact",
                  link:"/contact"
               },
            ]
         }
      }
   }
</script>
