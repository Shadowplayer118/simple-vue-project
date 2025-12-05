<template>
  <header class="w-full bg-white text-teal-500 fixed top-0 z-50 shadow-md">
    <div class="container mx-auto px-6 py-4 flex items-center justify-between">

      <!-- Logo -->
      <h1 class="text-xl font-bold">Mangoos PT</h1>

      <!-- Hamburger button (mobile) -->
      <button 
        @click="isOpen = !isOpen" 
        class="md:hidden focus:outline-none"
      >
        <svg 
          v-if="!isOpen"
          class="w-6 h-6" 
          fill="none" 
          stroke="currentColor" 
          viewBox="0 0 24 24" 
          xmlns="http://www.w3.org/2000/svg"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
        </svg>
        <svg 
          v-else
          class="w-6 h-6" 
          fill="none" 
          stroke="currentColor" 
          viewBox="0 0 24 24" 
          xmlns="http://www.w3.org/2000/svg"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
        </svg>
      </button>

      <!-- Navigation -->
      <nav 
        :class="{'block': isOpen, 'hidden': !isOpen}" 
        class="absolute top-full left-0 w-full bg-white md:bg-transparent md:static md:flex md:gap-6 md:w-auto md:items-center"
      >
        <a class="block px-6 py-2 hover:text-teal-600 transition md:inline" href="#home" @click="isOpen = false">Home</a>
        <a class="block px-6 py-2 hover:text-teal-600 transition md:inline" href="#about" @click="isOpen = false">About Us</a>
        <a class="block px-6 py-2 hover:text-teal-600 transition md:inline" href="#services" @click="isOpen = false">Services</a>
        <a class="block px-6 py-2 hover:text-teal-600 transition md:inline" href="#doctors" @click="isOpen = false">Our Doctors</a>
        <a class="block px-6 py-2 hover:text-teal-600 transition md:inline" href="#insurance" @click="isOpen = false">Accepted Insurance</a>
        <a class="block px-6 py-2 hover:text-teal-600 transition md:inline" href="#contact" @click="isOpen = false">Contact Us</a>
      </nav>

    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue';

const isOpen = ref(false);
</script>

<style>
/* Smooth scrolling for anchor links */
html {
  scroll-behavior: smooth;
}
</style>
