<!-- InsuranceSection.vue -->
<template>
  <section class="relative py-12 overflow-hidden" id="insurance">
    
    <!-- Background Image + Overlay -->
    <div 
      class="absolute inset-0 bg-cover bg-center"
      :style="{ backgroundImage: `url(${chiro1})` }"
    >
      <div class="absolute inset-0 bg-linear-to-br from-teal-900 via-teal-800 to-cyan-900 opacity-96"></div>
    </div>

    <!-- Decorative Elements -->
    <div class="absolute top-10 left-10 w-72 h-72 bg-cyan-400 opacity-10 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-10 right-10 w-80 h-80 bg-teal-400 opacity-10 rounded-full blur-3xl animate-pulse delay-1000"></div>

    <!-- Main Content -->
    <div class="relative container mx-auto px-6">

      <!-- Section Title -->
      <div class="text-center mb-8 max-w-4xl mx-auto">
        <div class="inline-block px-4 py-2 bg-white rounded-full border-2 border-teal-300 mb-3 shadow-lg">
          <span class="text-teal-700 text-sm font-bold flex items-center gap-2">
            <span class="text-lg">🏥</span>
            Insurance Coverage
          </span>
        </div>
        
        <h2 class="text-3xl md:text-4xl font-black text-teal mb-3 drop-shadow-lg">
          Insurance <span class="text-teal-200">Accepted</span>
        </h2>
        
        <div class="flex items-center justify-center gap-2 mb-3">
          <div class="w-10 h-1 bg-teal-300 rounded-full"></div>
          <div class="w-2 h-2 bg-teal-300 rounded-full"></div>
          <div class="w-12 h-1 bg-cyan-300 rounded-full"></div>
          <div class="w-2 h-2 bg-cyan-300 rounded-full"></div>
          <div class="w-10 h-1 bg-teal-300 rounded-full"></div>
        </div>
        
        <p class="text-teal text-sm md:text-base leading-relaxed drop-shadow-md">
          We accept a wide variety of insurance providers to ensure you receive the care you need.
        </p>
      </div>

      <!-- Trust Indicators - FIXED VISIBILITY -->
      <div class="flex justify-center gap-3 mb-8 flex-wrap">
        <div class="flex items-center gap-2 bg-white rounded-full px-4 py-2 shadow-lg border-2 border-teal-400">
          <div class="w-7 h-7 rounded-full bg-linear-to-br from-teal-500 to-cyan-500 flex items-center justify-center shadow-md">
            <svg class="w-4 h-4 text-teal" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/>
            </svg>
          </div>
          <span class="text-teal-800 text-xs font-bold">No-Fault Claims</span>
        </div>
        <div class="flex items-center gap-2 bg-white rounded-full px-4 py-2 shadow-lg border-2 border-cyan-400">
          <div class="w-7 h-7 rounded-full bg-linear-to-br from-cyan-500 to-teal-500 flex items-center justify-center shadow-md">
            <svg class="w-4 h-4 text-teal" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/>
            </svg>
          </div>
          <span class="text-cyan-800 text-xs font-bold">Workers Comp</span>
        </div>
        <div class="flex items-center gap-2 bg-white rounded-full px-4 py-2 shadow-lg border-2 border-teal-400">
          <div class="w-7 h-7 rounded-full bg-linear-to-br from-teal-500 to-cyan-500 flex items-center justify-center shadow-md">
            <svg class="w-4 h-4 text-teal" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/>
            </svg>
          </div>
          <span class="text-teal-800 text-xs font-bold">Personal Injury</span>
        </div>
      </div>

      <!-- Insurance Grid - SMALLER & MORE COMPACT (5 Cards Only) -->
      <div class="flex justify-center mb-8">
        <div class="flex flex-wrap justify-center gap-4 max-w-3xl">
          
          <!-- Insurance Item 1 -->
          <div class="group flex flex-col items-center cursor-pointer">
            <div class="relative">
              <div class="absolute -inset-1 bg-linear-to-br from-teal-400 via-cyan-400 to-teal-500 rounded-2xl blur opacity-50 group-hover:opacity-80 transition duration-300"></div>
              <div class="relative bg-white rounded-2xl p-4 shadow-xl group-hover:shadow-2xl transform group-hover:scale-110 transition-all duration-300 w-24 h-24 flex items-center justify-center border-2 border-teal-200">
                <img 
                  src="https://via.placeholder.com/100x60?text=Ins+1" 
                  alt="Insurance Provider 1" 
                  class="w-16 h-auto object-contain"
                />
              </div>
            </div>
            <span class="mt-2 text-white font-bold text-xs drop-shadow-lg bg-teal-700 bg-opacity-80 px-3 py-1 rounded-full">Insurance 1</span>
          </div>

          <!-- Insurance Item 2 -->
          <div class="group flex flex-col items-center cursor-pointer">
            <div class="relative">
              <div class="absolute -inset-1 bg-linear-to-br from-cyan-400 via-teal-400 to-cyan-500 rounded-2xl blur opacity-50 group-hover:opacity-80 transition duration-300"></div>
              <div class="relative bg-white rounded-2xl p-4 shadow-xl group-hover:shadow-2xl transform group-hover:scale-110 transition-all duration-300 w-24 h-24 flex items-center justify-center border-2 border-cyan-200">
                <img 
                  src="https://via.placeholder.com/100x60?text=Ins+2" 
                  alt="Insurance Provider 2" 
                  class="w-16 h-auto object-contain"
                />
              </div>
            </div>
            <span class="mt-2 text-white font-bold text-xs drop-shadow-lg bg-cyan-700 bg-opacity-80 px-3 py-1 rounded-full">Insurance 2</span>
          </div>

          <!-- Insurance Item 3 -->
          <div class="group flex flex-col items-center cursor-pointer">
            <div class="relative">
              <div class="absolute -inset-1 bg-linear-to-br from-teal-400 via-cyan-400 to-teal-500 rounded-2xl blur opacity-50 group-hover:opacity-80 transition duration-300"></div>
              <div class="relative bg-white rounded-2xl p-4 shadow-xl group-hover:shadow-2xl transform group-hover:scale-110 transition-all duration-300 w-24 h-24 flex items-center justify-center border-2 border-teal-200">
                <img 
                  src="https://via.placeholder.com/100x60?text=Ins+3" 
                  alt="Insurance Provider 3" 
                  class="w-16 h-auto object-contain"
                />
              </div>
            </div>
            <span class="mt-2 text-white font-bold text-xs drop-shadow-lg bg-teal-700 bg-opacity-80 px-3 py-1 rounded-full">Insurance 3</span>
          </div>

          <!-- Insurance Item 4 -->
          <div class="group flex flex-col items-center cursor-pointer">
            <div class="relative">
              <div class="absolute -inset-1 bg-linear-to-br from-cyan-400 via-teal-400 to-cyan-500 rounded-2xl blur opacity-50 group-hover:opacity-80 transition duration-300"></div>
              <div class="relative bg-white rounded-2xl p-4 shadow-xl group-hover:shadow-2xl transform group-hover:scale-110 transition-all duration-300 w-24 h-24 flex items-center justify-center border-2 border-cyan-200">
                <img 
                  src="https://via.placeholder.com/100x60?text=Ins+4" 
                  alt="Insurance Provider 4" 
                  class="w-16 h-auto object-contain"
                />
              </div>
            </div>
            <span class="mt-2 text-white font-bold text-xs drop-shadow-lg bg-cyan-700 bg-opacity-80 px-3 py-1 rounded-full">Insurance 4</span>
          </div>

          <!-- Insurance Item 5 -->
          <div class="group flex flex-col items-center cursor-pointer">
            <div class="relative">
              <div class="absolute -inset-1 bg-linear-to-br from-teal-400 via-cyan-400 to-teal-500 rounded-2xl blur opacity-50 group-hover:opacity-80 transition duration-300"></div>
              <div class="relative bg-white rounded-2xl p-4 shadow-xl group-hover:shadow-2xl transform group-hover:scale-110 transition-all duration-300 w-24 h-24 flex items-center justify-center border-2 border-teal-200">
                <img 
                  src="https://via.placeholder.com/100x60?text=Ins+5" 
                  alt="Insurance Provider 5" 
                  class="w-16 h-auto object-contain"
                />
              </div>
            </div>
            <span class="mt-2 text-white font-bold text-xs drop-shadow-lg bg-teal-700 bg-opacity-80 px-3 py-1 rounded-full">Insurance 5</span>
          </div>

        </div>
      </div>

      <!-- Call to Action Card - COMPACT -->
      <div class="max-w-2xl mx-auto">
        <div class="relative">
          <div class="absolute -inset-0.5 bg-linear-to-br from-teal-300 via-cyan-300 to-teal-300 rounded-2xl blur opacity-50"></div>
          <div class="relative bg-white rounded-2xl p-5 md:p-6 border-2 border-teal-200 shadow-xl">
            <div class="text-center">
              <h3 class="text-xl md:text-2xl font-black text-gray-900 mb-2 flex items-center justify-center gap-2">
                <span class="text-2xl">📋</span>
                Don't See Your Insurance?
              </h3>
              <p class="text-gray-600 text-sm mb-4 max-w-lg mx-auto leading-relaxed">
                Contact us to verify coverage. We work with many providers to ensure you get the care you deserve.
              </p>
              <div class="flex flex-col sm:flex-row gap-3 justify-center">
                <a 
                  href="tel:7185850888" 
                  class="inline-flex items-center justify-center gap-2 bg-linear-to-br from-teal-600 to-cyan-600 hover:from-teal-700 hover:to-cyan-700 text-teal font-bold py-2.5 px-6 rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 transform hover:scale-105 cursor-pointer text-sm"
                >
                  <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                  </svg>
                  Call (718) 585-0888
                </a>
                <a 
                  href="#contact" 
                  class="inline-flex items-center justify-center gap-2 bg-white hover:bg-gray-50 text-teal-700 font-bold py-2.5 px-6 rounded-xl border-2 border-teal-600 hover:border-teal-700 transition-all duration-300 cursor-pointer shadow-md hover:shadow-lg text-sm"
                >
                  <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                  </svg>
                  Contact Us
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<script setup>
import chiro1 from '@/assets/images/chiro-1.jpg'
</script>

<style scoped>
/* Pulse Animation */
@keyframes pulse {
  0%, 100% {
    opacity: 0.3;
  }
  50% {
    opacity: 0.5;
  }
}

.animate-pulse {
  animation: pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

.delay-1000 {
  animation-delay: 1s;
}
</style>