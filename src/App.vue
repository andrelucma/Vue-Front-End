<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import BlogMain from './components/BlogMain.vue'
</script>

<template>
  <div>
  <p>        
    <a href="" target="_blank" class="header_button">Blog</a>
    <a href="" target="_blank" class="header_button">Sobre</a>    
    <a href="" target="_blank" class="header_button">Descrição</a>    
  </p>    
      <img src="/vite.svg" class="logo" alt="Vite logo" />    
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />    
  </div>  
  <BlogMain msg="André Marques" />  
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.header_button {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
</style>
