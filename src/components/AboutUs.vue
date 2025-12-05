<!-- AboutUs.vue -->
<template>
  <section class="py-16 bg-linear-to-br from-gray-50 via-red-50/20 to-gray-50 relative overflow-hidden" id="about">
    
    <!-- Decorative background elements -->
    <div class="absolute top-10 left-10 w-72 h-72 bg-red-200 opacity-20 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-10 right-10 w-80 h-80 bg-teal-200 opacity-20 rounded-full blur-3xl animate-pulse delay-1000"></div>
    <div class="absolute top-1/2 right-1/4 w-64 h-64 bg-cyan-100 opacity-15 rounded-full blur-3xl"></div>
    
    <div class="container mx-auto px-6 md:px-12 relative">
      <div class="max-w-4xl mx-auto w-full">
        
        <!-- Title Section -->
        <div class="text-center mb-12 space-y-3">
          <div class="inline-block px-4 py-2 bg-linear-to-r from-red-50 to-red-100 rounded-full border-2 border-red-200 shadow-md">
            <span class="text-gray-700 text-sm font-semibold flex items-center gap-2">
              <span class="text-lg">🏥</span>
              About Our Practice
            </span>
          </div>
          
          <h2 class="text-4xl md:text-5xl font-black leading-tight">
            <span class="text-transparent bg-clip-text bg-linear-to-r from-red-500 to-red-600">Mangoos</span>
            <span class="text-gray-900"> Physical Therapy</span>
          </h2>
          
          <div class="flex items-center justify-center gap-2">
            <div class="w-12 h-1 bg-linear-to-r from-red-400 to-red-500 rounded-full"></div>
            <div class="w-2 h-2 bg-red-400 rounded-full"></div>
            <div class="w-16 h-1 bg-linear-to-r from-teal-400 to-cyan-400 rounded-full"></div>
            <div class="w-2 h-2 bg-teal-400 rounded-full"></div>
            <div class="w-12 h-1 bg-linear-to-r from-teal-400 to-teal-500 rounded-full"></div>
          </div>
        </div>

        <!-- Content Card -->
        <div class="relative mx-auto">
          <!-- Decorative gradient border -->
          <div class="absolute -inset-1 bg-linear-to-br from-red-300 via-teal-300 to-cyan-300 opacity-30 rounded-3xl blur"></div>
          
          <!-- Main content -->
          <div class="relative bg-white rounded-3xl shadow-2xl p-6 md:p-8 border border-gray-100">
            
            <!-- Icon Row -->
            <div class="flex items-center justify-center gap-6 mb-6">
              <div class="flex flex-col items-center">
                <div class="w-14 h-14 rounded-full bg-linear-to-br from-teal-400 to-teal-600 flex items-center justify-center shadow-lg mb-2">
                  <span class="text-2xl">💪</span>
                </div>
                <span class="text-xs font-bold text-gray-600">Orthopedic</span>
              </div>
              <div class="flex flex-col items-center">
                <div class="w-14 h-14 rounded-full bg-linear-to-br from-red-400 to-red-600 flex items-center justify-center shadow-lg mb-2">
                  <span class="text-2xl">⚕️</span>
                </div>
                <span class="text-xs font-bold text-gray-600">Sports</span>
              </div>
              <div class="flex flex-col items-center">
                <div class="w-14 h-14 rounded-full bg-linear-to-br from-cyan-400 to-cyan-600 flex items-center justify-center shadow-lg mb-2">
                  <span class="text-2xl">🔧</span>
                </div>
                <span class="text-xs font-bold text-gray-600">Holistic</span>
              </div>
            </div>

            <div class="text-gray-700 text-base leading-relaxed space-y-4">
              <p class="relative pl-4 border-l-4 border-teal-400">
                <span class="font-bold text-teal-700">Mangoos Physical Therapy (MPT)</span> is a full service Orthopedic and Sports Physical Therapy private practice. 
                We offer top-tier care for all orthopedic, sports, accident and work related injuries and conditions. 
                MPT specializes in <span class="font-semibold text-red-600">Workers Compensation, No Fault claims and Personal Injury cases</span>. 
                Our administrative staff works closely with the injured person's physician, attorney and insurance company allowing the individual to focus entirely on complete recovery.
              </p>
              
              <div class="bg-linear-to-r from-teal-50 to-cyan-50 rounded-2xl p-4 border border-teal-200">
                <p class="text-sm">
                  Unlike most clinics, we use a <span class="font-bold text-teal-700">holistic approach</span> to treat the whole person and not just their injury or condition. 
                  Our facility includes a physician, chiropractor and acupuncturist that enhance our therapy services. 
                  Our goal is to offer a natural non-invasive approach to healing by avoiding addictive drugs or unnecessary surgery.
                </p>
              </div>
              
              <div class="flex items-start gap-3 bg-linear-to-r from-red-50 to-red-100/50 rounded-2xl p-4 border border-red-200">
                <div class="shrink-0 w-10 h-10 rounded-full bg-red-500 flex items-center justify-center shadow-md">
                  <span class="text-xl">🚗</span>
                </div>
                <p class="text-sm pt-1">
                  <span class="font-bold text-red-700">Express Door-to-Door Service:</span> MPT offers a very convenient pick-up service. 
                  Patients relax and ride comfortably in the care of our professional driver to and from their appointments.
                </p>
              </div>
            </div>

            <!-- Decorative quote accent -->
            <div class="mt-6 pt-6 border-t border-gray-200 flex items-center justify-center gap-3">
              <div class="w-10 h-0.5 bg-linear-to-r from-red-400 to-red-500"></div>
              <span class="text-gray-500 font-bold italic text-sm">Committed to Your Complete Recovery</span>
              <div class="w-10 h-0.5 bg-linear-to-r from-teal-400 to-cyan-400"></div>
            </div>
          </div>
        </div>

        <!-- Call to Action -->
        <div class="mt-8 text-center">
          <a 
            href="#contact" 
            class="inline-flex items-center gap-2 bg-linear-to-r from-teal-600 to-cyan-600 hover:from-teal-700 hover:to-cyan-700 text-white font-bold py-3 px-8 rounded-xl shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:scale-105 cursor-pointer"
          >
            Schedule Your Appointment
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"/>
            </svg>
          </a>
        </div>

      </div>
    </div>
  </section>
</template>

<script setup>
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