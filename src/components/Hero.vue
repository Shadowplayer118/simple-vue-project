<!-- Hero.vue -->
<template>
  <section class="relative w-full min-h-[85vh] flex items-center justify-center overflow-hidden pt-16" id="home">
    
    <!-- Background Image with Overlay -->
    <div 
      class="absolute inset-0 bg-cover bg-center"
      :style="{ backgroundImage: `url(${hcBackground})` }"
    >
      <div class="absolute inset-0 bg-teal-900 opacity-85"></div>
    </div>

    <!-- Animated Background Elements -->
    <div class="absolute top-20 right-10 w-72 h-72 bg-teal-400 opacity-20 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-20 left-10 w-96 h-96 bg-cyan-400 opacity-20 rounded-full blur-3xl animate-pulse delay-1000"></div>

    <!-- Content Container -->
    <div class="relative container mx-auto px-4 sm:px-6 lg:px-8 py-8">
      <div class="flex flex-col lg:flex-row items-center justify-between gap-8 max-w-7xl mx-auto">
        
        <!-- Left Content -->
        <div class="lg:w-5/12 text-center lg:text-left space-y-5 animate-fade-in">
          
          <!-- Badge -->
          <div class="inline-flex items-center gap-2 px-4 py-2 bg-teal-600 bg-opacity-90 backdrop-blur-md rounded-full border border-teal-400 border-opacity-50 shadow-lg">
            <span class="text-xl">🏥</span>
            <span class="text-white text-sm font-bold drop-shadow-md">Professional Physical Therapy Services</span>
          </div>
          
          <!-- Main Heading -->
          <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-white leading-tight hero-shadow">
            Bringing Exceptional Care
            <span class="block mt-2 text-teal-200">
              to Our Community
            </span>
          </h1>
          
          <!-- Subheading -->
          <p class="text-lg sm:text-xl text-white opacity-95 leading-relaxed max-w-xl mx-auto lg:mx-0 hero-shadow-light">
            Expert rehabilitation and wellness solutions tailored to your recovery journey
          </p>
          
          <!-- CTA Buttons -->
          <div class="flex flex-col sm:flex-row gap-3 justify-center lg:justify-start pt-3">
            <a 
              href="tel:7185850888"
              class="inline-flex items-center justify-center gap-2 bg-white hover:bg-gray-50 text-teal-700 font-bold py-3 px-6 rounded-xl shadow-2xl transition-all duration-300 transform hover:scale-105 cursor-pointer"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
              </svg>
              Call (718) 585-0888
            </a>
            
            <a 
              href="#services"
              class="inline-flex items-center justify-center gap-2 bg-teal-600 bg-opacity-90 hover:bg-teal-700 text-white font-semibold py-3 px-6 rounded-xl border-2 border-white border-opacity-30 hover:border-opacity-60 transition-all duration-300 cursor-pointer"
            >
              Our Services
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
            </a>
          </div>
        </div>

        <!-- Right Content - Image with Organic Blob Shape -->
        <div class="lg:w-6/12 lg:pl-8 relative max-w-lg animate-slide-in">
          <!-- Blob Image -->
          <div class="relative blob-shape overflow-hidden shadow-2xl transform hover:scale-105 transition-transform duration-500">
            <!-- Decorative glow -->
            <div class="absolute -inset-2 bg-linear-to-r from-teal-400 to-cyan-400 blob-shape blur-xl opacity-60"></div>
            
            <!-- Image container with blob shape -->
            <div class="relative bg-white p-2 blob-shape">
              <img 
                :src="nurse2"
                alt="Professional Physical Therapy Care"
                class="w-full h-auto object-cover blob-inner"
              />
            </div>
          </div>

          <!-- Stats Overlay - Outside but Positioned on Top of Image at Hips -->
          <div class="absolute top-[75%] left-6 right-1 bg-linear-to-br from-teal-600 to-teal-700 backdrop-blur-md rounded-2xl p-4 shadow-2xl border-2 border-teal-400">
            <div class="grid grid-cols-3 gap-4 text-center">
              <div>
                <div class="text-2xl font-bold text-white">15+</div>
                <div class="text-xs text-teal-100 font-medium">Years</div>
              </div>
              <div class="border-l border-r border-teal-400">
                <div class="text-2xl font-bold text-white">500+</div>
                <div class="text-xs text-teal-100 font-medium">Patients</div>
              </div>
              <div>
                <div class="text-2xl font-bold text-white">100%</div>
                <div class="text-xs text-teal-100 font-medium">Care</div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script setup>
import hcBackground from '@/assets/images/hc-background.png'
import nurse2 from '@/assets/images/nurse2.png'
</script>

<style scoped>
/* Organic Blob Shape */
.blob-shape {
  border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
  animation: morph 8s ease-in-out infinite;
}

.blob-inner {
  border-radius: 58% 42% 32% 68% / 58% 32% 68% 42%;
}

/* Blob morphing animation */
@keyframes morph {
  0% {
    border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
  }
  
  50% {
    border-radius: 30% 60% 70% 40% / 50% 60% 30% 60%;
  }
  
  100% {
    border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
  }
}

/* Enhanced text shadows */
.hero-shadow {
  text-shadow: 
    2px 2px 4px rgba(0,0,0,0.3),
    4px 4px 12px rgba(0,0,0,0.4);
}

.hero-shadow-light {
  text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
}

/* Fade In Animation */
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Slide In Animation */
@keyframes slideIn {
  from {
    opacity: 0;
    transform: translateX(30px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

/* Pulse Animation */
@keyframes pulse {
  0%, 100% {
    opacity: 0.3;
  }
  50% {
    opacity: 0.5;
  }
}

/* Animation Classes */
.animate-fade-in {
  animation: fadeIn 1s ease-out;
}

.animate-slide-in {
  animation: slideIn 1s ease-out 0.3s both;
}

.animate-pulse {
  animation: pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

.delay-1000 {
  animation-delay: 1s;
}
</style>