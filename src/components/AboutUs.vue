<template>
  <section class="py-24 bg-gradient-to-b from-white via-gray-50 to-white relative overflow-hidden" id="about">
    
    <!-- Decorative background elements -->
    <div class="absolute top-20 left-10 w-72 h-72 bg-red-100/20 rounded-full blur-3xl"></div>
    <div class="absolute bottom-20 right-10 w-96 h-96 bg-teal-100/20 rounded-full blur-3xl"></div>
    
    <div class="container mx-auto px-6 md:px-12 relative flex items-center justify-center min-h-screen">
      <div class="max-w-5xl mx-auto w-full">
        
        <!-- Title Section -->
        <div class="text-center mb-16 space-y-6">
          <div class="inline-block px-5 py-2 bg-gradient-to-r from-red-50 to-teal-50 rounded-full border border-red-200/50 mb-2">
            <span class="text-gray-700 text-sm font-semibold">About Our Practice</span>
          </div>
          
          <h2 class="text-5xl md:text-7xl font-black leading-tight">
            <span class="bg-gradient-to-r from-red-400 to-red-500 bg-clip-text text-transparent">Mangoos</span>
            <span class="text-gray-900"> Physical Therapy</span>
          </h2>
          
          <div class="flex items-center justify-center gap-2">
            <div class="w-16 h-1 bg-gradient-to-r from-transparent to-red-400 rounded-full"></div>
            <div class="w-2 h-2 bg-red-400 rounded-full"></div>
            <div class="w-24 h-1 bg-gradient-to-r from-red-400 to-teal-400 rounded-full"></div>
            <div class="w-2 h-2 bg-teal-400 rounded-full"></div>
            <div class="w-16 h-1 bg-gradient-to-r from-teal-400 to-transparent rounded-full"></div>
          </div>
        </div>

        <!-- Content Card -->
        <div class="relative">
          <!-- Decorative gradient border -->
          <div class="absolute -inset-0.5 bg-gradient-to-r from-red-400 via-teal-400 to-cyan-400 rounded-3xl blur opacity-20"></div>
          
          <!-- Main content -->
          <div class="relative bg-white rounded-3xl shadow-2xl p-10 md:p-16 border border-gray-100">
            <p class="text-gray-700 text-lg md:text-xl leading-relaxed space-y-8">
              <span class="block">
                Mangoos Physical Therapy (MPT) is a full service Orthopedic and Sports Physical Therapy private practice. 
                We offer top-tier care for all orthopedic, sports, accident and work related injuries and conditions. 
                MPT specializes in Workers Compensation, No Fault claims and Personal Injury cases. 
                Our administrative staff also works closely with the injured person's physician, attorney and insurance company allowing the individual to focus entirely on his or her complete recovery.
              </span>
              
              <span class="block">
                Unlike most clinics, we use a holistic approach to treat the whole person and not just their injury or condition. 
                Our facility includes a physician, chiropractor and acupuncturist that enhance our therapy services. 
                Our goal is to offer a natural non-invasive approach to healing by avoiding addictive drugs or unnecessary surgery.
              </span>
              
              <span class="block">
                MPT offers a very convenient express door to door pick up service. 
                Patients relax and ride comfortably in the care of our professional driver to and from their appointments.
              </span>
            </p>

            <!-- Decorative quote accent -->
            <div class="mt-10 pt-10 border-t border-gray-200 flex items-center justify-center gap-3">
              <div class="w-12 h-0.5 bg-gradient-to-r from-transparent to-red-400"></div>
              <svg class="w-8 h-8 text-red-400/30" fill="currentColor" viewBox="0 0 24 24">
                <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/>
              </svg>
              <span class="text-gray-500 font-medium italic">Committed to Your Complete Recovery</span>
              <svg class="w-8 h-8 text-teal-400/30 transform rotate-180" fill="currentColor" viewBox="0 0 24 24">
                <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/>
              </svg>
              <div class="w-12 h-0.5 bg-gradient-to-r from-teal-400 to-transparent"></div>
            </div>
          </div>
        </div>

        <!-- Call to Action -->
        <div class="mt-16 text-center">
          <a 
            href="#contact" 
            class="inline-flex items-center gap-2 bg-gradient-to-r from-red-500 to-teal-500 hover:from-red-600 hover:to-teal-600 text-white font-bold py-5 px-12 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300 transform hover:scale-105"
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
/* Smooth transitions */
a {
  transition: all 0.3s ease;
}
</style>