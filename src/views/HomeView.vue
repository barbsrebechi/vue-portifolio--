<template>
  <div class="flex items-center justify-center min-h-screen bg-pink-100 text-pink-900 p-6">
    <div class="bg-pink-200 rounded-xl shadow-md p-8 w-full sm:max-w-2xl md:max-w-3xl lg:max-w-4xl text-center space-y-6">
      <div class="w-40 h-40 mx-auto rounded-full overflow-hidden">
        <img :src="fotoPerfil" alt="Foto de perfil" class="w-full h-full object-cover">
      </div>

      <h1 class="text-4xl font-semibold">Bem-vindo(a)!</h1>
      <p class="text-lg">
        Olá, me chamo <strong>Barbara</strong>, sou uma jovem estudante de ADS na UNIMAR.
        Aqui compartilho meus projetos, ideias e trabalhos acadêmicos ou não.
      </p>
    </div>
  </div>
</template>

<script>
import foto from '@/assets/img/barbara.jpeg';

export default {
  name: 'HomeView',
  data() {
    return {
      fotoPerfil: foto
    };
  }
};
</script>



