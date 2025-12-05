<template>
  <section class="py-16 bg-gray-50" id="doctors">
    <div class="container mx-auto px-6 max-w-6xl">

      <!-- Section Title -->
      <div class="text-center mb-12">
        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">
          Our Specialty Doctors
        </h2>
        <p class="text-gray-700 text-lg md:text-xl">
          Meet the expert physical therapists providing care at Mangoos Physical Therapy.
        </p>
      </div>

      <!-- Doctors Cards -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 justify-center">

        <!-- Doctor 1 -->
        <div class="bg-white rounded-lg shadow-lg p-6 flex flex-col items-center text-center">
          <img 
            src="https://source.unsplash.com/200x200/?male,doctor" 
            alt="Michael Mangubat" 
            class="w-32 h-32 rounded-full mb-4 object-cover"
          />
          <h3 class="text-xl font-semibold text-gray-800">Michael Mangubat, PT</h3>
          <p class="text-gray-600 mt-2">Physical Therapist</p>
        </div>

        <!-- Doctor 2 -->
        <div class="bg-white rounded-lg shadow-lg p-6 flex flex-col items-center text-center">
          <img 
            src="https://source.unsplash.com/200x200/?female,doctor" 
            alt="Miriam Opena" 
            class="w-32 h-32 rounded-full mb-4 object-cover"
          />
          <h3 class="text-xl font-semibold text-gray-800">Miriam Opena, PT</h3>
          <p class="text-gray-600 mt-2">Physical Therapist</p>
        </div>

      </div>

    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
/* Optional: hover scale effect */
div.bg-white:hover {
  transform: scale(1.03);
  transition: transform 0.3s ease;
}
</style>
