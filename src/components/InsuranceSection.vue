<template>
  <section class="py-16 bg-white" id="insurance">
    <div class="container mx-auto px-6 max-w-6xl">

      <!-- Section Title -->
      <div class="text-center mb-12">
        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">
          Insurance Accepted
        </h2>
        <p class="text-gray-700 text-lg md:text-xl">
          We accept a variety of insurance providers for your convenience.
        </p>
      </div>

      <!-- Insurance Grid -->
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-8 items-center text-center">

        <!-- Example Insurance 1 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+1" 
            alt="Insurance 1" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-gray-700 font-medium">Insurance 1</span>
        </div>

        <!-- Example Insurance 2 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+2" 
            alt="Insurance 2" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-gray-700 font-medium">Insurance 2</span>
        </div>

        <!-- Example Insurance 3 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+3" 
            alt="Insurance 3" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-gray-700 font-medium">Insurance 3</span>
        </div>

        <!-- Example Insurance 4 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+4" 
            alt="Insurance 4" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-gray-700 font-medium">Insurance 4</span>
        </div>

        <!-- Example Insurance 5 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+5" 
            alt="Insurance 5" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-gray-700 font-medium">Insurance 5</span>
        </div>

        <!-- Example Insurance 6 -->
        <div class="flex flex-col items-center">
          <img 
            src="https://via.placeholder.com/100x60?text=Insurance+6" 
            alt="Insurance 6" 
            class="w-24 h-auto object-contain mb-2"
          />
          <span class="text-gray-700 font-medium">Insurance 6</span>
        </div>

      </div>

    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
/* Optional: hover scale effect for logos */
div.flex:hover img {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}
</style>
