<script setup lang="ts">
  // This starter template is using Vue 3 <script setup> SFCs
  // Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
  import navbar from './components/navbar.vue'
  import nav_title from './components/nav_title.vue'
  import servers from './components/servers.vue'
  import current_server from './components/current_server.vue' 
  
</script>

<template>
  <navbar>
    <div class="fixed left-0 top-0 h-full w-80 md:h-8 md:w-full bg-[#202225] grid grid-cols-[1fr,3fr] md:grid-cols-1 grid-rows-[2rem]">
      <nav_title>Discord</nav_title>

      <div class=""></div> <!-- empty grid-->
      
      <servers></servers>

      <current_server></current_server>
    </div>
  </navbar>
</template>

<style scoped>

</style>
