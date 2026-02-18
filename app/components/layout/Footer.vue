<script setup lang="ts"></script>

<template>
  <footer class="bg-gray-900 text-white px-6 py-8">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row md:justify-between md:items-start gap-6">
      
      <!-- Column 1: Logo + About -->
      <div>
        <h2 class="text-xl font-bold mb-2">MyApp</h2>
        <p class="text-gray-400 text-sm">Aplikasi keren buat belajar Nuxt + Tailwind.</p>
      </div>

      <!-- Column 2: Quick Links -->
      <div>
        <h3 class="font-semibold mb-2">Quick Links</h3>
        <ul class="space-y-1">
          <li><NuxtLink to="#" class="hover:text-gray-300">Home</NuxtLink></li>
          <li><NuxtLink to="#" class="hover:text-gray-300">About</NuxtLink></li>
          <li><NuxtLink to="#" class="hover:text-gray-300">Contact</NuxtLink></li>
        </ul>
      </div>

      <!-- Column 3: Contact -->
      <div>
        <h3 class="font-semibold mb-2">Contact</h3>
        <p class="text-gray-400 text-sm">Email: info@myapp.com</p>
        <p class="text-gray-400 text-sm">Phone: +62 812 3456 7890</p>
      </div>

    </div>

    <!-- Copyright -->
    <div class="mt-8 text-center text-gray-500 text-sm">
      &copy; 2026 MyApp. All rights reserved.
    </div>
  </footer>
</template>