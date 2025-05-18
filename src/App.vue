<template>
  <div class="flex flex-col min-h-screen bg-gray-100">
    <Navbar />

    <div class="flex-grow container mx-auto px-4 py-6 pb-32">
      <router-view />
    </div>

    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/NavbarComponent.vue'
import Footer from './components/FooterComponent.vue'
</script>

