<!-- Header.vue -->
<template>
  <header class="fixed top-0 left-0 right-0 z-50 bg-white shadow-md border-b border-gray-100">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        
        <!-- Logo -->
        <div class="shrink-0 flex items-center gap-2">
          <div class="w-9 h-9 rounded-lg bg-linear-to-r from-teal-500 to-cyan-500 flex items-center justify-center shadow-md">
            <span class="text-white text-lg font-black">M</span>
          </div>
          <h1 class="text-xl font-black text-transparent bg-clip-text bg-linear-to-r from-teal-600 to-cyan-600 cursor-pointer hover:from-teal-700 hover:to-cyan-700 transition-all duration-200">
            Mangoos PT
          </h1>
        </div>

        <!-- Desktop Navigation -->
        <nav class="hidden lg:flex items-center space-x-1">
          <a 
            href="#home" 
            @click="setActive('home')"
            :class="activeSection === 'home' ? 'text-teal-600 bg-teal-50' : 'text-gray-700 hover:text-teal-600 hover:bg-teal-50'"
            class="px-4 py-2 rounded-lg transition-all duration-200 font-medium cursor-pointer relative group"
          >
            Home
            <span 
              :class="activeSection === 'home' ? 'w-3/4 left-1/8' : 'w-0 left-1/2'" 
              class="absolute bottom-0 h-0.5 bg-linear-to-r from-teal-500 to-cyan-500 group-hover:w-3/4 group-hover:left-1/8 transition-all duration-300 rounded-full"
            ></span>
          </a>
          
          <a 
            href="#about" 
            @click="setActive('about')"
            :class="activeSection === 'about' ? 'text-teal-600 bg-teal-50' : 'text-gray-700 hover:text-teal-600 hover:bg-teal-50'"
            class="px-4 py-2 rounded-lg transition-all duration-200 font-medium cursor-pointer relative group"
          >
            About Us
            <span 
              :class="activeSection === 'about' ? 'w-3/4 left-1/8' : 'w-0 left-1/2'" 
              class="absolute bottom-0 h-0.5 bg-linear-to-r from-teal-500 to-cyan-500 group-hover:w-3/4 group-hover:left-1/8 transition-all duration-300 rounded-full"
            ></span>
          </a>
          
          <a 
            href="#services" 
            @click="setActive('services')"
            :class="activeSection === 'services' ? 'text-teal-600 bg-teal-50' : 'text-gray-700 hover:text-teal-600 hover:bg-teal-50'"
            class="px-4 py-2 rounded-lg transition-all duration-200 font-medium cursor-pointer relative group"
          >
            Services
            <span 
              :class="activeSection === 'services' ? 'w-3/4 left-1/8' : 'w-0 left-1/2'" 
              class="absolute bottom-0 h-0.5 bg-linear-to-r from-teal-500 to-cyan-500 group-hover:w-3/4 group-hover:left-1/8 transition-all duration-300 rounded-full"
            ></span>
          </a>
          
          <a 
            href="#doctors" 
            @click="setActive('doctors')"
            :class="activeSection === 'doctors' ? 'text-teal-600 bg-teal-50' : 'text-gray-700 hover:text-teal-600 hover:bg-teal-50'"
            class="px-4 py-2 rounded-lg transition-all duration-200 font-medium cursor-pointer relative group"
          >
            Our Doctors
            <span 
              :class="activeSection === 'doctors' ? 'w-3/4 left-1/8' : 'w-0 left-1/2'" 
              class="absolute bottom-0 h-0.5 bg-linear-to-r from-teal-500 to-cyan-500 group-hover:w-3/4 group-hover:left-1/8 transition-all duration-300 rounded-full"
            ></span>
          </a>
          
          <a 
            href="#insurance" 
            @click="setActive('insurance')"
            :class="activeSection === 'insurance' ? 'text-teal-600 bg-teal-50' : 'text-gray-700 hover:text-teal-600 hover:bg-teal-50'"
            class="px-4 py-2 rounded-lg transition-all duration-200 font-medium cursor-pointer relative group"
          >
            Insurance
            <span 
              :class="activeSection === 'insurance' ? 'w-3/4 left-1/8' : 'w-0 left-1/2'" 
              class="absolute bottom-0 h-0.5 bg-linear-to-r from-teal-500 to-cyan-500 group-hover:w-3/4 group-hover:left-1/8 transition-all duration-300 rounded-full"
            ></span>
          </a>
          
          <a 
            href="#contact" 
            @click="setActive('contact')"
            class="ml-2 px-6 py-2.5 rounded-lg bg-linear-to-r from-teal-600 to-cyan-600 text-white hover:from-teal-700 hover:to-cyan-700 transition-all duration-200 font-semibold shadow-lg hover:shadow-xl cursor-pointer transform hover:scale-105"
          >
            Contact Us
          </a>
        </nav>

        <!-- Mobile menu button -->
        <button 
          @click="isOpen = !isOpen" 
          class="lg:hidden inline-flex items-center justify-center p-2 rounded-lg text-gray-700 hover:bg-teal-50 hover:text-teal-600 focus:outline-none focus:ring-2 focus:ring-teal-500 transition-colors duration-200 cursor-pointer"
        >
          <svg 
            v-if="!isOpen"
            class="w-6 h-6" 
            fill="none" 
            stroke="currentColor" 
            viewBox="0 0 24 24"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
          <svg 
            v-else
            class="w-6 h-6" 
            fill="none" 
            stroke="currentColor" 
            viewBox="0 0 24 24"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile Navigation -->
    <div 
      :class="isOpen ? 'max-h-screen opacity-100' : 'max-h-0 opacity-0'" 
      class="lg:hidden overflow-hidden transition-all duration-300 ease-in-out bg-linear-to-b from-white to-teal-50/30 border-t border-gray-100"
    >
      <nav class="px-4 py-4 space-y-2">
        <a 
          href="#home" 
          @click="setActive('home'); isOpen = false" 
          :class="activeSection === 'home' ? 'bg-teal-100 text-teal-700 font-bold' : 'text-gray-700 hover:bg-teal-100 hover:text-teal-700'"
          class="block px-4 py-3 rounded-lg transition-colors duration-200 font-medium cursor-pointer"
        >
          Home
        </a>
        <a 
          href="#about" 
          @click="setActive('about'); isOpen = false" 
          :class="activeSection === 'about' ? 'bg-teal-100 text-teal-700 font-bold' : 'text-gray-700 hover:bg-teal-100 hover:text-teal-700'"
          class="block px-4 py-3 rounded-lg transition-colors duration-200 font-medium cursor-pointer"
        >
          About Us
        </a>
        <a 
          href="#services" 
          @click="setActive('services'); isOpen = false" 
          :class="activeSection === 'services' ? 'bg-teal-100 text-teal-700 font-bold' : 'text-gray-700 hover:bg-teal-100 hover:text-teal-700'"
          class="block px-4 py-3 rounded-lg transition-colors duration-200 font-medium cursor-pointer"
        >
          Services
        </a>
        <a 
          href="#doctors" 
          @click="setActive('doctors'); isOpen = false" 
          :class="activeSection === 'doctors' ? 'bg-teal-100 text-teal-700 font-bold' : 'text-gray-700 hover:bg-teal-100 hover:text-teal-700'"
          class="block px-4 py-3 rounded-lg transition-colors duration-200 font-medium cursor-pointer"
        >
          Our Doctors
        </a>
        <a 
          href="#insurance" 
          @click="setActive('insurance'); isOpen = false" 
          :class="activeSection === 'insurance' ? 'bg-teal-100 text-teal-700 font-bold' : 'text-gray-700 hover:bg-teal-100 hover:text-teal-700'"
          class="block px-4 py-3 rounded-lg transition-colors duration-200 font-medium cursor-pointer"
        >
          Insurance
        </a>
        <a 
          href="#contact" 
          @click="setActive('contact'); isOpen = false" 
          class="block px-4 py-3 rounded-lg bg-linear-to-r from-teal-600 to-cyan-600 text-white hover:from-teal-700 hover:to-cyan-700 transition-all duration-200 font-semibold text-center shadow-md cursor-pointer"
        >
          Contact Us
        </a>
      </nav>
    </div>
  </header>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const isOpen = ref(false)
const activeSection = ref('home')

const setActive = (section) => {
  activeSection.value = section
}

// Scroll spy - automatically detects which section is in view
const handleScroll = () => {
  const sections = ['home', 'about', 'services', 'doctors', 'insurance', 'contact']
  const scrollPosition = window.scrollY + 100 // offset for header height

  for (const section of sections) {
    const element = document.getElementById(section)
    if (element) {
      const offsetTop = element.offsetTop
      const offsetBottom = offsetTop + element.offsetHeight

      if (scrollPosition >= offsetTop && scrollPosition < offsetBottom) {
        activeSection.value = section
        break
      }
    }
  }
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
  handleScroll() // Check initial position
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>

<style scoped>
</style>