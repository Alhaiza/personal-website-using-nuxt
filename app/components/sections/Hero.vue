<script setup lang="ts"></script>

<template>
  <!-- HERO SECTION -->
  <section class="container-app mt-10">
    <div
      class="bg-white rounded-[3rem] shadow-md overflow-hidden grid grid-cols-1 md:grid-cols-2"
    >
      <!-- LEFT CONTENT -->
      <div class="p-10 space-y-6 flex flex-col justify-center">
        <h1 class="text-4xl md:text-5xl font-bold leading-tight">
          Hi, I’m Haiza 👋 <br />
          Fullstack Developer
        </h1>

        <p class="text-gray-500 text-lg">
          I build scalable APIs with Laravel, modern UI with Nuxt, and
          cross-platform mobile apps using Flutter.
        </p>

        <!-- BUTTONS -->
        <div class="flex flex-col sm:flex-row gap-3">
          <button
            class="px-6 py-3 rounded-full bg-sky-500 text-white font-semibold hover:bg-sky-600 transition"
          >
            View Projects →
          </button>

          <button
            class="px-6 py-3 rounded-full border border-gray-300 text-gray-600 hover:bg-gray-100 transition"
          >
            Contact Me
          </button>
        </div>
      </div>

      <!-- RIGHT IMAGE -->
      <div class="h-[300px] md:h-auto">
        <img
          src="https://images.unsplash.com/photo-1518770660439-4636190af475"
          class="w-full h-full object-cover"
          alt="Developer Workspace"
        />
      </div>
    </div>
  </section>
</template>
