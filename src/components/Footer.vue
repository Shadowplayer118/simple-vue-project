<!-- Footer.vue -->
<template>
  <footer class="bg-linear-to-br from-gray-900 via-gray-800 to-gray-900 text-white py-12 relative overflow-hidden" id="contact">
    
    <!-- Decorative background elements -->
    <div class="absolute top-10 left-10 w-96 h-96 bg-teal-500 opacity-5 rounded-full blur-3xl"></div>
    <div class="absolute bottom-10 right-10 w-80 h-80 bg-cyan-500 opacity-5 rounded-full blur-3xl"></div>
    
    <div class="container mx-auto px-6 max-w-6xl relative">
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10 mb-10">
        
        <!-- Logo & Tagline -->
        <div class="space-y-4">
          <div class="flex items-center gap-2 mb-3">
            <div class="w-10 h-10 rounded-xl bg-linear-to-br from-teal-500 to-cyan-500 flex items-center justify-center shadow-lg">
              <span class="text-white text-xl font-bold">M</span>
            </div>
            <h2 class="text-2xl font-black text-transparent bg-clip-text bg-linear-to-r from-teal-400 to-cyan-400">
              Mangoos PT
            </h2>
          </div>
          <p class="text-gray-400 text-sm leading-relaxed">
            Providing exceptional physical therapy care to help you achieve complete recovery and optimal wellness.
          </p>
          <div class="flex gap-3 pt-2">
            <a href="#" class="w-10 h-10 rounded-xl bg-linear-to-br from-teal-600 to-cyan-600 hover:from-teal-500 hover:to-cyan-500 flex items-center justify-center transition-all duration-300 cursor-pointer transform hover:scale-110 shadow-lg hover:shadow-xl">
              <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
              </svg>
            </a>
            <a href="#" class="w-10 h-10 rounded-xl bg-linear-to-br from-cyan-600 to-teal-600 hover:from-cyan-500 hover:to-teal-500 flex items-center justify-center transition-all duration-300 cursor-pointer transform hover:scale-110 shadow-lg hover:shadow-xl">
              <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                <path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/>
              </svg>
            </a>
            <a href="#" class="w-10 h-10 rounded-xl bg-linear-to-br from-teal-600 to-cyan-600 hover:from-teal-500 hover:to-cyan-500 flex items-center justify-center transition-all duration-300 cursor-pointer transform hover:scale-110 shadow-lg hover:shadow-xl">
              <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"/>
              </svg>
            </a>
          </div>
        </div>

        <!-- Quick Links -->
        <div>
          <h3 class="text-lg font-bold mb-4 text-transparent bg-clip-text bg-linear-to-r from-teal-400 to-cyan-400 flex items-center gap-2">
            <span class="text-teal-400">⚡</span>
            Quick Links
          </h3>
          <ul class="space-y-2">
            <li>
              <a href="#home" class="text-gray-400 hover:text-teal-400 transition duration-200 flex items-center gap-2 cursor-pointer text-sm group">
                <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
                </svg>
                Home
              </a>
            </li>
            <li>
              <a href="#about" class="text-gray-400 hover:text-teal-400 transition duration-200 flex items-center gap-2 cursor-pointer text-sm group">
                <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
                </svg>
                About Us
              </a>
            </li>
            <li>
              <a href="#services" class="text-gray-400 hover:text-teal-400 transition duration-200 flex items-center gap-2 cursor-pointer text-sm group">
                <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
                </svg>
                Our Services
              </a>
            </li>
            <li>
              <a href="#doctors" class="text-gray-400 hover:text-teal-400 transition duration-200 flex items-center gap-2 cursor-pointer text-sm group">
                <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
                </svg>
                Our Doctors
              </a>
            </li>
            <li>
              <a href="#insurance" class="text-gray-400 hover:text-teal-400 transition duration-200 flex items-center gap-2 cursor-pointer text-sm group">
                <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
                </svg>
                Insurance
              </a>
            </li>
          </ul>
        </div>

        <!-- Contact Info -->
        <div>
          <h3 class="text-lg font-bold mb-4 text-transparent bg-clip-text bg-linear-to-r from-teal-400 to-cyan-400 flex items-center gap-2">
            <span class="text-teal-400">📞</span>
            Contact Us
          </h3>
          <ul class="space-y-3 text-gray-400">
            <li class="flex items-start gap-2 group">
              <div class="w-8 h-8 rounded-lg bg-teal-600 bg-opacity-20 flex items-center justify-center shrink-0 group-hover:bg-opacity-30 transition-all duration-200">
                <svg class="w-4 h-4 text-teal-400" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                </svg>
              </div>
              <span class="text-sm">825 Walton Ave, Bronx NY 10451</span>
            </li>
            <li class="flex items-center gap-2 group">
              <div class="w-8 h-8 rounded-lg bg-cyan-600 bg-opacity-20 flex items-center justify-center shrink-0 group-hover:bg-opacity-30 transition-all duration-200">
                <svg class="w-4 h-4 text-cyan-400" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                </svg>
              </div>
              <a href="tel:7185850888" class="hover:text-teal-400 transition cursor-pointer text-sm font-semibold">718-585-0888</a>
            </li>
            <li class="flex items-center gap-2 group">
              <div class="w-8 h-8 rounded-lg bg-teal-600 bg-opacity-20 flex items-center justify-center shrink-0 group-hover:bg-opacity-30 transition-all duration-200">
                <svg class="w-4 h-4 text-teal-400" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                  <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                </svg>
              </div>
              <a href="mailto:mangoosphysicaltherapy@gmail.com" class="hover:text-teal-400 transition break-all cursor-pointer text-xs">
                mangoosphysicaltherapy@gmail.com
              </a>
            </li>
            <li class="flex items-start gap-2 group">
              <div class="w-8 h-8 rounded-lg bg-cyan-600 bg-opacity-20 flex items-center justify-center shrink-0 group-hover:bg-opacity-30 transition-all duration-200">
                <svg class="w-4 h-4 text-cyan-400" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd"/>
                </svg>
              </div>
              <span class="text-sm">Monday - Friday: 10:00 AM - 6:00 PM</span>
            </li>
          </ul>
        </div>

      </div>

      <!-- Bottom Bar -->
      <div class="border-t border-gray-700 pt-6">
        <div class="flex flex-col md:flex-row justify-between items-center gap-3">
          <p class="text-gray-400 text-xs">
            © 2024 Mangoos Physical Therapy. All rights reserved.
          </p>
          <div class="flex gap-5 text-xs">
            <a href="#" class="text-gray-400 hover:text-teal-400 transition cursor-pointer">Privacy Policy</a>
            <span class="text-gray-700">|</span>
            <a href="#" class="text-gray-400 hover:text-teal-400 transition cursor-pointer">Terms of Service</a>
          </div>
        </div>
      </div>

    </div>
  </footer>
</template>

<script setup>
</script>

<style scoped>
</style>