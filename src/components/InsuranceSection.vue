<template>
  <section class="relative py-16" id="insurance">
    
    <!-- Background Image + Gradient Overlay -->
    <div 
      class="absolute inset-0 bg-cover bg-center"
      :style="{ backgroundImage: `url(${chiro1})` }"
    >
      <div class="absolute inset-0 bg-gradient-to-b from-teal-300/30 via-teal-300/20 to-teal-300/70"></div>
    </div>

    <!-- Main Content -->
    <div class="relative container mx-auto px-6 max-w-6xl">

      <!-- Section Title -->
      <div class="text-center mb-12">
        <h2 class="text-4xl md:text-5xl font-bold text-white mb-4">
          Insurance Accepted
        </h2>
        <p class="text-teal-800 text-lg md:text-xl">
          We accept a variety of insurance providers for your convenience.
        </p>
      </div>

      <!-- Insurance Grid -->
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-8 justify-center text-center">
        <!-- Example Insurance 1 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+1" 
            alt="Insurance 1" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-teal-900 font-medium">Insurance 1</span>
        </div>

        <!-- Example Insurance 2 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+2" 
            alt="Insurance 2" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-teal-900 font-medium">Insurance 2</span>
        </div>

        <!-- Add more insurance items here -->

      </div>

    </div>
  </section>
</template>

<script setup>
import chiro1 from '@/assets/images/chiro-1.jpg';
</script>

<style scoped>
/* Optional: hover scale effect for logos */
div.flex:hover img {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}
</style>
