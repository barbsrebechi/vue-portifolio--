<template>
  <div class="min-h-screen bg-pink-100 text-pink-900 flex items-center justify-center p-6">
    <div class="bg-pink-200 rounded-xl shadow-md p-6 max-w-md w-full text-center space-y-4">

  
      <div class="w-32 h-32 mx-auto rounded-full overflow-hidden">
        <img :src="fotoPerfil" alt="Foto de perfil" class="w-full h-full object-cover">
      </div>

     
      <h1 class="text-3xl font-bold">Bem-vindo(a)!</h1>
      <p class="text-base">
        Olá! Meu nome é <strong>Seu Nome</strong>, sou um(a) desenvolvedor(a) apaixonado(a) por tecnologia e inovação.
        Aqui compartilho meus projetos, ideias e aprendizados.
      </p>
    </div>
  </div>
</template>

<script>
import foto from '@/assets/img/barbara.jpeg'; // Caminho correto usando alias "@"

export default {
  name: 'HomeView',
  data() {
    return {
      fotoPerfil: foto
    };
  }
};
</script>

<style scoped>
/* Estilos extras, se quiser */
</style>

