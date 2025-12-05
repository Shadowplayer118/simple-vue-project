<script setup lang="ts">
import { ref, onMounted, onUnmounted } from 'vue'
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import AboutUs from './components/AboutUs.vue'
import OurServices from './components/OurServices.vue'
import DoctorSection from './components/DoctorSection.vue'
import InsuranceSection from './components/InsuranceSection.vue'
import Footer from './components/Footer.vue'

const showScrollTop = ref(false)

const handleScroll = () => {
  showScrollTop.value = window.scrollY > 300
}

const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: 'smooth'
  })
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>

<template>
  <main class="min-h-screen bg-white relative">
    <Header />
    <Hero />
    <AboutUs />
    <OurServices />
    <DoctorSection />
    <InsuranceSection />
    <Footer />

    <!-- Scroll to Top Button -->
    <transition name="fade">
      <button
        v-if="showScrollTop"
        @click="scrollToTop"
        class="fixed bottom-8 right-8 z-50 w-14 h-14 bg-teal-600 hover:bg-teal-700 text-white rounded-full shadow-2xl hover:shadow-teal-500/50 transition-all duration-300 transform hover:scale-110 cursor-pointer flex items-center justify-center group"
        aria-label="Scroll to top"
      >
        <svg class="w-6 h-6 transform group-hover:-translate-y-1 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"/>
        </svg>
      </button>
    </transition>
  </main>
</template>

<style>
html {
  scroll-behavior: smooth;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s ease, transform 0.3s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
  transform: scale(0.8);
}
</style>