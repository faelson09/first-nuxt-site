<script setup lang="ts"></script>
<template>
<div class="flex flex-col items-center max-w-[100vw] overflow-hidden">
   <Navbar/>
   <main class="w-[calc(100vw-12px)] max-w-[1200px] flex flex-col items-center">
      <slot />
   </main>
   <Rodape/>
</div>
</template>
