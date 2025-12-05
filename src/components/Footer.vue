<template>
  <footer class="bg-gray-900 text-white py-12" id="contact">
    <div class="container mx-auto px-6 flex flex-col md:flex-row items-start md:items-center justify-between gap-8">

      <!-- Left: Logo -->
      <div class="flex items-center">
        <img 
          src="https://via.placeholder.com/150x50?text=Mangoos+Logo" 
          alt="Mangoos Physical Therapy Logo" 
          class="w-40 h-auto object-contain"
        />
      </div>

      <!-- Right: Contact Info -->
      <div class="text-left md:text-right space-y-1">
        <p class="font-semibold">© Mangoos Physical Therapy</p>
        <p>825 Walton Ave</p>
        <p>Bronx NY 10451</p>
        <p>Phone: 718-585-0888</p>
        <p>Fax: 718-585-0880</p>
        <p>Email: <a href="mailto:mangoosphysicaltherapy@gmail.com" class="underline hover:text-teal-400">mangoosphysicaltherapy@gmail.com</a></p>
        <p>Office Hours: Monday-Friday 10AM-6PM</p>
      </div>

    </div>
  </footer>
</template>

<script setup>
</script>

<style scoped>
/* Optional: hover effect for email */
a:hover {
  transition: color 0.3s ease;
}
</style>
