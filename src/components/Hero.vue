<template>
  <section class="relative w-full min-h-screen flex items-center overflow-hidden" id="home">
    
    <!-- Background Image + Enhanced Gradient Overlay -->
    <div 
      class="absolute inset-0 bg-cover bg-center scale-105"
      :style="{ backgroundImage: `url(${hcBackground})` }"
    >
      <div class="absolute inset-0 bg-gradient-to-br from-teal-400/70 via-teal-500/50 to-teal-600/30"></div>
    </div>

    <!-- Animated accent shapes -->
    <div class="absolute top-20 right-10 w-72 h-72 bg-teal-400/10 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-20 left-10 w-96 h-96 bg-cyan-400/10 rounded-full blur-3xl animate-pulse delay-1000"></div>

    <!-- Content -->
    <div class="relative container mx-auto px-6 py-16 flex flex-col md:flex-row items-center justify-between gap-12">
      
      <!-- Left side -->
      <div class="md:w-1/2 text-center md:text-left space-y-6 animate-fade-in">
        <div class="inline-block px-4 py-2 bg-white/10 backdrop-blur-sm rounded-full border border-white/20 mb-2">
          <span class="text-white/90 text-sm font-medium">🏥 Professional Physical Therapy Services</span>
        </div>
        
        <h1 class="text-5xl md:text-7xl font-black text-white leading-tight tracking-tight hero-shadow">
          Bringing Exceptional Care 
          <span class="block text-teal-200 mt-2">to Our Community</span>
        </h1>
        
        <p class="text-xl md:text-2xl font-medium text-white/95 leading-relaxed hero-shadow-light max-w-xl">
          Expert rehabilitation and wellness solutions tailored to your recovery journey at Mangoos Physical Therapy Clinic
        </p>
        
        <div class="flex flex-col sm:flex-row gap-4 pt-4">
          <a 
            href="tel:7185850888"
            class="group inline-flex items-center justify-center bg-white hover:bg-teal-50 text-teal-700 font-bold py-4 px-8 rounded-xl shadow-2xl hover:shadow-teal-500/50 transition-all duration-300 transform hover:scale-105"
          >
            <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 20 20">
              <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
            </svg>
            Call (718) 585-0888
          </a>
          
          <a 
            href="#services"
            class="inline-flex items-center justify-center bg-teal-600/80 backdrop-blur-sm hover:bg-teal-700 text-white font-semibold py-4 px-8 rounded-xl border-2 border-white/30 transition-all duration-300 hover:border-white/60"
          >
            Our Services
            <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
            </svg>
          </a>
        </div>
      </div>

      <!-- Right side image with modern card design -->
      <div class="md:w-1/2 relative animate-slide-in">
        <div class="relative rounded-2xl overflow-hidden shadow-2xl transform hover:scale-105 transition-transform duration-500">
          <!-- Decorative border -->
          <div class="absolute -inset-1 bg-gradient-to-r from-teal-400 to-cyan-400 rounded-2xl blur opacity-75"></div>
          
          <!-- Image container -->
          <div class="relative bg-white p-2 rounded-2xl">
            <img 
              :src="nurse2"
              alt="Professional Physical Therapy Care"
              class="w-full h-auto object-cover rounded-xl"
            />
            
            <!-- Stats overlay -->
            <div class="absolute bottom-6 left-6 right-6 bg-white/95 backdrop-blur-md rounded-xl p-4 shadow-lg">
              <div class="grid grid-cols-3 gap-4 text-center">
                <div>
                  <div class="text-2xl font-bold text-teal-700">15+</div>
                  <div class="text-xs text-gray-600">Years Experience</div>
                </div>
                <div class="border-l border-r border-gray-200">
                  <div class="text-2xl font-bold text-teal-700">500+</div>
                  <div class="text-xs text-gray-600">Happy Patients</div>
                </div>
                <div>
                  <div class="text-2xl font-bold text-teal-700">100%</div>
                  <div class="text-xs text-gray-600">Dedicated Care</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>

  </section>
</template>

<script setup>
import hcBackground from '@/assets/images/hc-background.png';
import nurse2 from '@/assets/images/nurse2.png';
</script>

<style scoped>
/* Enhanced text shadows */
.hero-shadow {
  text-shadow: 
    2px 2px 4px rgba(0,0,0,0.3),
    4px 4px 12px rgba(0,0,0,0.4);
}

.hero-shadow-light {
  text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
}

/* Animations */
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

@keyframes pulse {
  0%, 100% {
    opacity: 0.3;
  }
  50% {
    opacity: 0.5;
  }
}
</style>