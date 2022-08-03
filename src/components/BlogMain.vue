<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">Curtir {{ count }}</button>
    <div class="text-main">
      <p>
        Últimas do blog      
      </p>
    </div>    
  </div>

  <p>    
    <span class="text-info">Configura algumas dicas para tracionar sua carreira em Front-End</span><br>
    <a href="" target="_blank">5 dicas para sua carreira profissional</a>    
  </p>
  <p>    
    <span class="text-info">Configura algumas dicas para tracionar sua carreira em BackEnd</span><br>
    <a href="" target="_blank">5 dicas para sua carreira profissional</a>    
  </p>
    <p>    
    <span class="text-info">Configura algumas dicas para tracionar sua carreira em Arquitetura</span><br>
    <a href="" target="_blank">5 dicas para sua carreira profissional</a>    
  </p>
  <p class="read-the-docs">Ver Tudo</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.text-main{
  font-weight: bold
}
.text-info {
color: #000;
font-weight: bold /* negrito no texto */
}

</style>
