<script setup lang="ts"></script>

<template>
  <footer class="mb-10">
    <!-- Wrapper sama persis kayak section -->
    <div class="container-app">
      <!-- Card Footer -->
      <div class="bg-sky-500 text-white rounded-[3rem] shadow-lg px-10 py-10">
        <!-- Content -->
        <div class="flex flex-col md:flex-row justify-between gap-10">
          <!-- Column 1 -->
          <div>
            <h2 class="text-2xl font-bold mb-3">MyApp</h2>
            <p class="text-white/90 text-sm leading-relaxed">
              A simple portfolio built with Nuxt + Tailwind CSS.
            </p>
          </div>

          <!-- Column 2 -->
          <div>
            <h3 class="font-semibold mb-3">Contact</h3>

            <p class="flex items-center gap-2 text-sm">
              <UiAppIcon name="line-md:email" size="lg" />
              alqadrihaiza@gmail.com
            </p>

            <p class="text-sm mt-2">📞 +62 895-6182-04842</p>
          </div>
        </div>

        <!-- Divider -->
        <div class="border-t border-white/30 mt-8 pt-6 text-center text-sm">
          © 2026 Haiza. All rights reserved.
        </div>
      </div>
    </div>
  </footer>
</template>
