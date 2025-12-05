<!-- DoctorSection.vue -->
<template>
  <section class="py-20 bg-linear-to-br from-gray-50 via-teal-50/30 to-gray-50 relative overflow-hidden" id="doctors">
    
    <!-- Decorative background elements -->
    <div class="absolute top-10 left-20 w-96 h-96 bg-teal-200 opacity-20 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-10 right-20 w-80 h-80 bg-cyan-200 opacity-20 rounded-full blur-3xl animate-pulse delay-1000"></div>
    <div class="absolute top-1/2 left-1/4 w-64 h-64 bg-red-100 opacity-15 rounded-full blur-3xl"></div>
    
    <div class="container mx-auto px-6 max-w-6xl relative">

      <!-- Section Title -->
      <div class="text-center mb-16">
        <div class="inline-block px-5 py-2.5 bg-linear-to-br from-teal-50 to-cyan-50 rounded-full border-2 border-teal-200 mb-4 shadow-md">
          <span class="text-gray-700 text-sm font-semibold flex items-center gap-2">
            <span class="text-xl">👨‍⚕️</span>
            Meet Our Team
          </span>
        </div>
        
        <h2 class="text-5xl md:text-6xl font-black text-gray-900 mb-6">
          Our Specialty 
          <span class="text-transparent bg-clip-text bg-linear-to-br from-teal-600 to-cyan-600">Doctors</span>
        </h2>
        
        <div class="flex items-center justify-center gap-2 mb-6">
          <div class="w-12 h-1 bg-teal-400 rounded-full"></div>
          <div class="w-2 h-2 bg-teal-400 rounded-full"></div>
          <div class="w-16 h-1 bg-cyan-400 rounded-full"></div>
          <div class="w-2 h-2 bg-cyan-400 rounded-full"></div>
          <div class="w-12 h-1 bg-teal-400 rounded-full"></div>
        </div>
        
        <p class="text-gray-600 text-lg md:text-xl max-w-3xl mx-auto leading-relaxed">
          Expert physical therapists providing exceptional care at Mangoos Physical Therapy.
        </p>
      </div>

      <!-- Doctors Cards -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10 max-w-5xl mx-auto">

        <!-- Doctor 1 - Michael Mangubat -->
        <div class="group relative">
          <!-- Animated gradient border -->
          <div class="absolute -inset-1 bg-linear-to-br from-teal-400 via-cyan-400 to-teal-500 rounded-3xl blur opacity-40 group-hover:opacity-70 transition duration-500"></div>
          
          <!-- Card content -->
          <div class="relative bg-white rounded-3xl shadow-2xl overflow-hidden transform group-hover:scale-105 transition-all duration-500 border border-gray-100">
            
            <!-- Top accent bar -->
            <div class="h-2 bg-linear-to-br from-teal-500 via-cyan-400 to-teal-600"></div>
            
            <div class="p-8 flex flex-col items-center text-center">
              <!-- Profile image with decorative ring -->
              <div class="relative mb-6">
                <div class="absolute -inset-2 bg-linear-to-br from-teal-400 to-cyan-500 rounded-full blur-md opacity-50 group-hover:opacity-75 transition duration-300"></div>
                <div class="relative w-36 h-36 rounded-full overflow-hidden ring-4 ring-white shadow-xl">
                  <img 
                    src="https://source.unsplash.com/200x200/?male,doctor" 
                    alt="Michael Mangubat" 
                    class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500"
                  />
                </div>
                <!-- Verified badge -->
                <div class="absolute bottom-2 right-2 bg-teal-500 rounded-full p-2 shadow-lg ring-4 ring-white">
                  <svg class="w-5 h-5 text-white" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                </div>
              </div>
              
              <!-- Name and title -->
              <h3 class="text-2xl md:text-3xl font-black text-gray-900 mb-2">Michael Mangubat</h3>
              <p class="text-lg font-bold text-teal-600 mb-4 flex items-center gap-2">
                <span class="text-xl">🩺</span>
                Physical Therapist
              </p>
              
              <!-- Description -->
              <p class="text-gray-600 text-sm mb-6 leading-relaxed max-w-xs">
                Specializing in sports medicine and orthopedic rehabilitation with over 15 years of experience.
              </p>
              
              <!-- Specialties -->
              <div class="flex flex-wrap gap-2 justify-center mb-6">
                <span class="px-4 py-2 bg-linear-to-br from-teal-50 to-teal-100 text-teal-700 text-xs font-bold rounded-full border border-teal-200 shadow-sm">
                  Sports Medicine
                </span>
                <span class="px-4 py-2 bg-linear-to-br from-cyan-50 to-cyan-100 text-cyan-700 text-xs font-bold rounded-full border border-cyan-200 shadow-sm">
                  Orthopedic Care
                </span>
                <span class="px-4 py-2 bg-linear-to-br from-teal-50 to-cyan-50 text-teal-700 text-xs font-bold rounded-full border border-teal-200 shadow-sm">
                  Injury Prevention
                </span>
              </div>
              
              <!-- Contact button -->
              <button class="w-full bg-linear-to-br from-teal-600 to-cyan-600 hover:from-teal-700 hover:to-cyan-700 text-white font-bold py-3 px-6 rounded-xl shadow-lg hover:shadow-2xl transition-all duration-300 flex items-center justify-center gap-2">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"/>
                </svg>
                Book Appointment
              </button>
            </div>
          </div>
        </div>

        <!-- Doctor 2 - Miriam Opena -->
        <div class="group relative">
          <!-- Animated gradient border -->
          <div class="absolute -inset-1 bg-linear-to-br from-cyan-400 via-teal-400 to-cyan-500 rounded-3xl blur opacity-40 group-hover:opacity-70 transition duration-500"></div>
          
          <!-- Card content -->
          <div class="relative bg-white rounded-3xl shadow-2xl overflow-hidden transform group-hover:scale-105 transition-all duration-500 border border-gray-100">
            
            <!-- Top accent bar -->
            <div class="h-2 bg-linear-to-br from-cyan-500 via-teal-400 to-cyan-600"></div>
            
            <div class="p-8 flex flex-col items-center text-center">
              <!-- Profile image with decorative ring -->
              <div class="relative mb-6">
                <div class="absolute -inset-2 bg-linear-to-br from-cyan-400 to-teal-500 rounded-full blur-md opacity-50 group-hover:opacity-75 transition duration-300"></div>
                <div class="relative w-36 h-36 rounded-full overflow-hidden ring-4 ring-white shadow-xl">
                  <img 
                    src="https://source.unsplash.com/200x200/?female,doctor" 
                    alt="Miriam Opena" 
                    class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500"
                  />
                </div>
                <!-- Verified badge -->
                <div class="absolute bottom-2 right-2 bg-cyan-500 rounded-full p-2 shadow-lg ring-4 ring-white">
                  <svg class="w-5 h-5 text-white" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                </div>
              </div>
              
              <!-- Name and title -->
              <h3 class="text-2xl md:text-3xl font-black text-gray-900 mb-2">Miriam Opena</h3>
              <p class="text-lg font-bold text-cyan-600 mb-4 flex items-center gap-2">
                <span class="text-xl">🩺</span>
                Physical Therapist
              </p>
              
              <!-- Description -->
              <p class="text-gray-600 text-sm mb-6 leading-relaxed max-w-xs">
                Expert in rehabilitation and wellness programs, dedicated to helping patients achieve optimal recovery.
              </p>
              
              <!-- Specialties -->
              <div class="flex flex-wrap gap-2 justify-center mb-6">
                <span class="px-4 py-2 bg-linear-to-br from-cyan-50 to-cyan-100 text-cyan-700 text-xs font-bold rounded-full border border-cyan-200 shadow-sm">
                  Rehabilitation
                </span>
                <span class="px-4 py-2 bg-linear-to-br from-teal-50 to-teal-100 text-teal-700 text-xs font-bold rounded-full border border-teal-200 shadow-sm">
                  Wellness Programs
                </span>
                <span class="px-4 py-2 bg-linear-to-br from-cyan-50 to-teal-50 text-cyan-700 text-xs font-bold rounded-full border border-cyan-200 shadow-sm">
                  Pain Management
                </span>
              </div>
              
              <!-- Contact button -->
              <button class="w-full bg-linear-to-br from-cyan-600 to-teal-600 hover:from-cyan-700 hover:to-teal-700 text-white font-bold py-3 px-6 rounded-xl shadow-lg hover:shadow-2xl transition-all duration-300 flex items-center justify-center gap-2">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"/>
                </svg>
                Book Appointment
              </button>
            </div>
          </div>
        </div>

      </div>

      <!-- Bottom CTA Section -->
      <div class="mt-20 text-center">
        <div class="inline-block relative">
          <div class="absolute -inset-2 bg-linear-to-br from-teal-400 to-cyan-400 rounded-2xl blur opacity-40"></div>
          <div class="relative bg-linear-to-br from-teal-600 to-cyan-600 rounded-2xl p-8 shadow-2xl border border-teal-400">
            <h3 class="text-2xl md:text-3xl font-bold text-white mb-3">
              Ready to Start Your Recovery Journey?
            </h3>
            <p class="text-teal-100 mb-6 max-w-2xl mx-auto">
              Schedule a consultation with our expert physical therapists today.
            </p>
            <a 
              href="tel:7185850888" 
              class="inline-flex items-center gap-3 bg-white hover:bg-gray-50 text-teal-700 font-bold py-4 px-8 rounded-xl shadow-xl hover:shadow-2xl transition-all duration-300 transform hover:scale-105"
            >
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20">
                <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
              </svg>
              Call (718) 585-0888
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"/>
              </svg>
            </a>
          </div>
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