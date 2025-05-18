<template>
  <div class="min-h-screen bg-pink-100 text-pink-900 p-6 flex flex-col items-center">
    <div class="max-w-xl w-full space-y-8">
      <h1 class="text-4xl font-bold text-center">Contato</h1>

      <form class="bg-pink-200 p-6 rounded-xl shadow-md space-y-4">
        <div>
          <label class="block mb-1 font-semibold">Nome</label>
          <input type="text" placeholder="Seu nome" class="w-full p-2 rounded border border-pink-300 focus:outline-none focus:ring-2 focus:ring-pink-400">
        </div>
        <div>
          <label class="block mb-1 font-semibold">Email</label>
          <input type="email" placeholder="seu@email.com" class="w-full p-2 rounded border border-pink-300 focus:outline-none focus:ring-2 focus:ring-pink-400">
        </div>
        <div>
          <label class="block mb-1 font-semibold">Mensagem</label>
          <textarea rows="4" placeholder="Escreva sua mensagem..." class="w-full p-2 rounded border border-pink-300 focus:outline-none focus:ring-2 focus:ring-pink-400"></textarea>
        </div>
        <button type="submit" class="bg-pink-500 text-white px-4 py-2 rounded hover:bg-pink-600 transition">
          Enviar
        </button>
      </form>

      <div class="text-center">
        <h2 class="text-2xl font-semibold mb-2">Redes Sociais</h2>
        <div class="flex justify-center gap-6 text-pink-700 text-xl">
          <a href="https://www.instagram.com/barbaraa.rebechi" target="_blank" class="hover:text-pink-900">Instagram</a>
          <a href="https://www.linkedin.com/in/barbara-rebechi" target="_blank" class="hover:text-pink-900">LinkedIn</a>
          <a href="https://github.com/barbsrebechi" target="_blank" class="hover:text-pink-900">GitHub</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContatoView',
};
</script>

