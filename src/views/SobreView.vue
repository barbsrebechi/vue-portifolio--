<template>
  <div class="min-h-screen bg-pink-100 text-pink-900 p-6">
    <div class="max-w-6xl mx-auto space-y-10">
      <header class="text-center">
        <h1 class="text-5xl font-bold mb-2">Sobre Mim</h1>
        <p class="text-lg">Minha trajetória na Área</p>
      </header>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <section class="bg-pink-200 rounded-xl shadow-md p-6">
          <h2 class="text-2xl font-semibold mb-3">Habilidades</h2>
          <ul class="list-disc list-inside text-lg space-y-1">
            <li>HTML, CSS, Tailwind, JavaScript</li>
            <li>Vue.js, Vite, Git e GitHub</li>
            <li>Consumo de APIs e integração com backend</li>
          </ul>
        </section>

        <section class="bg-pink-200 rounded-xl shadow-md p-6">
          <h2 class="text-2xl font-semibold mb-3">O que estudo?</h2>
          <p class="text-lg">
            Estudante de Análise e Desenvolvimento de Sistemas, focada em entrar na área como desenvolvedora back-end.
          </p>
        </section>

        <section class="bg-pink-200 rounded-xl shadow-md p-6">
          <h2 class="text-2xl font-semibold mb-3">Como cheguei até aqui?</h2>
          <p class="text-lg">
            Comecei a estudar programação em 2021, ao cair de paraquedas no curso médio/técnico da Etec. Me interessei pela área e decidi continuar nessa jornada.
          </p>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SobreView',
};
</script>


