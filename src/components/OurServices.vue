<!-- OurServices.vue -->
<template>
  <section class="py-16 bg-linear-to-br from-white via-teal-50/30 to-white relative overflow-hidden" id="services">

    <!-- Decorative background elements -->
    <div class="absolute top-20 right-20 w-96 h-96 bg-teal-200 opacity-20 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-20 left-20 w-80 h-80 bg-cyan-200 opacity-20 rounded-full blur-3xl animate-pulse delay-1000"></div>
    <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-64 h-64 bg-red-100 opacity-10 rounded-full blur-3xl"></div>

    <!-- Main Content -->
    <div class="container mx-auto px-6 max-w-6xl relative">

      <!-- Section Title -->
      <div class="text-center mb-12">
        <div class="inline-block px-5 py-2.5 bg-linear-to-br from-teal-50 to-cyan-50 rounded-full border-2 border-teal-200 mb-4 shadow-md">
          <span class="text-gray-700 text-sm font-semibold flex items-center gap-2">
            <span class="text-lg">🏥</span>
            What We Offer
          </span>
        </div>
        
        <h2 class="text-4xl md:text-5xl font-black text-gray-900 mb-4">
          Our <span class="text-transparent bg-clip-text bg-linear-to-br from-teal-600 to-cyan-600">Services</span>
        </h2>
        
        <div class="flex items-center justify-center gap-2 mb-4">
          <div class="w-12 h-1 bg-teal-400 rounded-full"></div>
          <div class="w-2 h-2 bg-teal-400 rounded-full"></div>
          <div class="w-16 h-1 bg-cyan-400 rounded-full"></div>
          <div class="w-2 h-2 bg-cyan-400 rounded-full"></div>
          <div class="w-12 h-1 bg-teal-400 rounded-full"></div>
        </div>
        
        <p class="text-gray-600 text-base md:text-lg max-w-2xl mx-auto">
          State-of-the-art facilities with expert therapists dedicated to your recovery.
        </p>
      </div>

      <!-- First Service Block: Electrical Stimulation -->
      <div class="flex flex-col lg:flex-row items-center justify-center gap-8 mb-16">
        
        <!-- Left: Text -->
        <div class="lg:w-1/2 relative">
          <div class="absolute -inset-1 bg-linear-to-br from-teal-300 to-cyan-300 rounded-3xl blur opacity-30"></div>
          <div class="relative bg-linear-to-br from-teal-50 to-cyan-50/50 rounded-3xl shadow-xl p-6 md:p-8 border-2 border-teal-100">
            <!-- Top accent -->
            <div class="absolute top-0 left-0 right-0 h-1 bg-linear-to-br from-teal-500 via-cyan-400 to-teal-600 rounded-t-3xl"></div>
            
            <div class="flex items-center gap-3 mb-5">
              <div class="w-12 h-12 rounded-xl bg-linear-to-br from-teal-500 to-cyan-500 flex items-center justify-center shadow-lg">
                <span class="text-2xl">⚡</span>
              </div>
              <h3 class="text-2xl md:text-3xl font-black text-teal-900">
                Electrical Stimulation
              </h3>
            </div>
            
            <ul class="grid grid-cols-1 md:grid-cols-2 gap-2 text-gray-700 text-sm">
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Transcutaneous Electrical Nerve Stimulation</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Functional Electrical Stimulation</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Therapeutic Exercises</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Thermal Modalities</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Hot Moist Pack</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Therapeutic Ultrasound</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Cryotherapy</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Athletic Taping</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Hand Therapy</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Post-Operative Physical Therapy</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Spine & Back Educational Programs</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Sports Injury Rehabilitation</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Work Injury Rehabilitation</span>
              </li>
              <li class="flex items-start gap-2">
                <svg class="w-4 h-4 text-teal-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
                <span>Pre-operative Physical Therapy</span>
              </li>
            </ul>
          </div>
        </div>

        <!-- Right: Image -->
        <div class="lg:w-1/2 flex justify-center">
          <div class="relative max-w-sm">
            <div class="absolute -inset-2 bg-linear-to-br from-teal-400 to-cyan-500 rounded-3xl blur-lg opacity-40"></div>
            <img 
              :src="vector1"
              alt="Electrical Stimulation" 
              class="relative w-full rounded-3xl shadow-2xl transform hover:scale-105 transition duration-500"
            />
          </div>
        </div>
      </div>

      <!-- Second Service Block: Specialty Services -->
      <div class="flex flex-col-reverse lg:flex-row items-center justify-center gap-8">
        
        <!-- Left: Image -->
        <div class="lg:w-1/2 flex justify-center">
          <div class="relative max-w-sm">
            <div class="absolute -inset-2 bg-linear-to-br from-cyan-400 to-teal-500 rounded-3xl blur-lg opacity-40"></div>
            <img 
              :src="vector2" 
              alt="Specialty Services" 
              class="relative w-full rounded-3xl shadow-2xl transform hover:scale-105 transition duration-500"
            />
          </div>
        </div>

        <!-- Right: Text -->
        <div class="lg:w-1/2 relative">
          <div class="absolute -inset-1 bg-linear-to-br from-cyan-300 to-teal-300 rounded-3xl blur opacity-30"></div>
          <div class="relative bg-linear-to-br from-cyan-50 to-teal-50/50 rounded-3xl shadow-xl p-6 md:p-8 border-2 border-cyan-100">
            <!-- Top accent -->
            <div class="absolute top-0 left-0 right-0 h-1 bg-linear-to-br from-cyan-500 via-teal-400 to-cyan-600 rounded-t-3xl"></div>
            
            <div class="flex items-center gap-3 mb-5">
              <div class="w-12 h-12 rounded-xl bg-linear-to-br from-cyan-500 to-teal-500 flex items-center justify-center shadow-lg">
                <span class="text-2xl">🏥</span>
              </div>
              <h3 class="text-2xl md:text-3xl font-black text-cyan-900">
                Specialty Services
              </h3>
            </div>
            
            <div class="max-h-80 overflow-y-auto pr-2 hide-scrollbar">
              <ul class="grid grid-cols-1 gap-2 text-gray-700 text-sm">
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>AC Joint Injuries</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Achilles Tendinitis</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Achilles Tendon Rupture</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>ACL Injuries</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Ankle Fracture Surgery</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Ankle Fractures</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Ankle Fusion Surgery</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Anterior Cervical Corpectomy</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Arthritis & Reconstruction Surgery</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Arthroscopic Cartilage Repair</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Arthroscopic Chondrosplasty</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Arthroscopic Elbow Debridement</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Arthroscopic Rotator Cuff Repair</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Cartilage Restoration</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Artificial Disk Replacement</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Olecranon Bursa Aspiration</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Shoulder Instability</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Avascular Necrosis</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Bankart Repair</span>
                </li>
                <li class="flex items-start gap-2">
                  <svg class="w-4 h-4 text-cyan-600 mt-0.5 shrink-0" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                  </svg>
                  <span>Bicep Tendon Tear</span>
                </li>
              </ul>
            </div>
          </div>
        </div>

      </div>

    </div>
  </section>
</template>

<script setup>
import vector1 from '@/assets/images/vector-1.jpg'
import vector2 from '@/assets/images/vector-2.png'
</script>

<style scoped>
.hide-scrollbar::-webkit-scrollbar {
  display: none;
}

.hide-scrollbar {
  -ms-overflow-style: none;
  scrollbar-width: none;
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

.animate-pulse {
  animation: pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

.delay-1000 {
  animation-delay: 1s;
}
</style>