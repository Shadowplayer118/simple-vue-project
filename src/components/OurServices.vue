<template>
  <section class="relative py-16" id="services">

    <!-- Background Image + Gradient Overlay -->
    <div 
      class="absolute inset-0 bg-cover bg-center"
      :style="{ backgroundImage: `url('https://source.unsplash.com/1600x900/?physical-therapy,hospital')` }"
    >
      <div class="absolute inset-0 bg-gradient-to-r from-white/70 via-white/50 to-white/70"></div>
    </div>

    <!-- Main Content -->
    <div class="relative container mx-auto px-6 max-w-6xl">

      <!-- Section Title -->
      <div class="text-center mb-12">
        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">
          Our Services
        </h2>
        <p class="text-gray-700 text-lg md:text-xl">
          Mangoos Physical Therapy clinics are equipped with facilities and therapists to provide the following services.
        </p>
      </div>

      <!-- First Flex Block: Electrical Stimulation -->
      <div class="flex flex-col md:flex-row items-center gap-8 mb-16">
        
        <!-- Left: Text -->
        <div class="md:w-1/2">
          <h3 class="text-2xl font-semibold text-gray-800 mb-4">Electrical Stimulation</h3>
          <ul class="list-disc list-inside text-gray-700 space-y-1">
            <li>Transcutaneous Electrical Nerve Stimulation</li>
            <li>Functional Electrical Stimulation</li>
            <li>Therapeutic Exercises</li>
            <li>Thermal Modalities</li>
            <li>Hot Moist Pack</li>
            <li>Therapeutic Ultrasound</li>
            <li>Cryotherapy</li>
            <li>Athletic Taping</li>
            <li>Hand Therapy</li>
            <li>Post-Operative Physical Therapy</li>
            <li>Spine & Back Educational Programs</li>
            <li>Sports Injury Rehabilitation</li>
            <li>Work Injury Rehabilitation</li>
            <li>Pre-operative Physical Therapy</li>
          </ul>
        </div>

        <!-- Right: Image -->
        <div class="md:w-1/2">
          <img 
            src="https://source.unsplash.com/600x400/?physical-therapy,clinic" 
            alt="Electrical Stimulation" 
            class="w-full rounded-lg shadow-lg"
          />
        </div>
      </div>

      <!-- Second Flex Block: Specialty Services -->
      <div class="flex flex-col md:flex-row items-center gap-8">
        
        <!-- Left: Image -->
        <div class="md:w-1/2">
          <img 
            src="https://source.unsplash.com/600x400/?specialist,therapy" 
            alt="Specialty Services" 
            class="w-full rounded-lg shadow-lg"
          />
        </div>

        <!-- Right: Text -->
        <div class="md:w-1/2">
          <h3 class="text-2xl font-semibold text-gray-800 mb-4">Specialty Services</h3>
          <ul class="list-disc list-inside text-gray-700 space-y-1 max-h-96 overflow-y-auto">
            <li>AC Joint Injuries</li>
            <li>Achilles Tendinities - Achilles Insertional Calcific Tendinopathy (ACIT)</li>
            <li>Achilles Tendon Rupture</li>
            <li>Achilles Tendonitis</li>
            <li>ACL Injuries</li>
            <li>Ankle Fracture Surgery</li>
            <li>Ankle Fractures (Broken Ankle)</li>
            <li>Ankle Fusion Surgery</li>
            <li>Anterior Cervical Corpectomy & Discectomy</li>
            <li>Arthritis & Adult Reconstruction Surgery</li>
            <li>Arthroscopic Articular Cartilage Repair</li>
            <li>Arthroscopic Chondrosplasty</li>
            <li>Arthroscopic Debridement of the Elbow</li>
            <li>Arthroscopic Rotator Cuff Repair</li>
            <li>Articular Cartilage Restoration</li>
            <li>Artificial Disk Replacement (ADR)</li>
            <li>Aspiration of the Olecranon Bursa</li>
            <li>Atraumatic Shoulder Instability</li>
            <li>Avascular Necrosis (Osteonecrosis)</li>
            <li>Bankart Repair</li>
            <li>Bicep Tendon Tear</li>
          </ul>
        </div>

      </div>

    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
/* Smooth scrolling for long lists */
ul {
  scroll-behavior: smooth;
}
</style>
