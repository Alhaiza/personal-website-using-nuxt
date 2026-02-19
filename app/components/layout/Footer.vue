<script setup lang="ts"></script>

<template>
  <footer class="bg-orange-600 text-white px-6 py-8">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row md:justify-between md:items-start gap-6">
      
      <!-- Column 1: Logo + About -->
      <div>
        <h2 class="text-xl font-bold mb-2">MyApp</h2>
        <p class="text-white text-sm">Aplikasi keren buat belajar Nuxt + Tailwind.</p>
      </div>

      <!-- Column 3: Contact -->
      <div>
        <h3 class="font-semibold mb-2">Contact</h3>
       <p class="text-white text-sm flex items-center gap-2">
        <UiAppIcon name="line-md:email" size="lg" class="text-white"/>
        alqadrihaiza@gmail.com
      </p>
        <p class="text-white text-sm">Phone: +62895618204842</p>
      </div>

    </div>

    <!-- Copyright -->
    <div class="mt-8 text-center text-white text-sm">
      &copy; 2026 MyApp. All rights reserved.
    </div>
  </footer>
</template>