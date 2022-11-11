<template>
    <div 
    class="h-full w-full bg-[#202225] flex flex-col justify-start items-center gap-2"
  > <!-- nav_button_container -->
      <nav_button 
      class="bg-[url(./assets/vite.svg)] bg-no-repeat bg-[length:65%] bg-center"
      ></nav_button>
      
      <div class="bg-[#2f3136] w-[50%] aspect-[8/1] my-[4%] rounded-full"></div>
      
      <nav_button 
        class="bg-[url(./assets/vue.svg)] bg-no-repeat bg-[length:65%] bg-center"
      ></nav_button>

      <nav_button 
        class="bg-[url(./assets/Tailwind.svg)] bg-no-repeat bg-[length:65%] bg-center"
      ></nav_button>

      <nav_button 
        class="bg-[url(./assets/TypeScript.svg)] bg-no-repeat bg-cover bg-center"
      ></nav_button>

      <nav_button 
        class="bg-[url(./assets/vue.svg)] bg-no-repeat bg-[length:65%] bg-center"
      ></nav_button>


  </div>
</template>

<script setup lang="ts">
    import nav_button from './nav_button.vue'
</script>