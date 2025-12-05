<template>
  <section class="relative w-full min-h-screen flex items-center" id="home">
    
    <!-- Background Image + Gradient Overlay -->
    <div 
      class="absolute inset-0 bg-cover bg-center"
      :style="{ backgroundImage: `url(${hcBackground})` }"
    >
        <div class="absolute inset-0 bg-gradient-to-b from-white/30 via-white/20 to-white/80"></div>
    </div>

    <!-- Content -->
    <div class="relative container mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-8">
      
      <!-- Left side -->
      <div class="md:w-1/2 text-center md:text-left">
        <h1 class="text-4xl md:text-5xl font-extrabold text-gray-900 leading-snug mb-4">
          Bringing Exceptional Care <br /> to our Community.
        </h1>
        <p class="text-xl md:text-2xl font-medium text-gray-700 mb-6">
          Mangoos Physical Therapy Clinic
        </p>
        <a 
          href="tel:7185850888"
          class="inline-block bg-teal-500 hover:bg-teal-600 text-white font-semibold py-3 px-6 rounded shadow transition"
        >
          Need an appointment? Call 7185850888
        </a>
      </div>

      <!-- Right side image -->
      <div class="md:w-1/2">
        <img 
          :src="nurse3"  
          alt="Clinic Hero" 
          class="w-full rounded-lg shadow-lg"
        />
      </div>

    </div>

  </section>
</template>

<script setup>
import hcBackground from '@/assets/images/hc-background.png';
import nurse3 from '@/assets/images/nurse3.png';
</script>
