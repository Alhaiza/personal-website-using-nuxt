<script setup lang="ts"></script>

<template>
  <section class="container-app mt-28">
    <div
      class="bg-white rounded-[3rem] shadow-md overflow-hidden grid grid-cols-1 md:grid-cols-2"
    >
      <!-- RIGHT -->
      <div class="h-[300px] md:h-auto">
        <img
          src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d"
          class="w-full h-full object-cover"
          alt="Hero Image"
        />
      </div>
      <!-- LEFT -->
      <div class="p-10 space-y-6">
        <h1 class="text-4xl font-bold leading-tight">
          Let’s Take Your <br />
          Business to the Next Level
        </h1>

        <p class="text-gray-500">
          Leave your email and we’ll reach out with tailored advice.
        </p>

        <!-- FORM -->
        <div class="flex flex-col sm:flex-row gap-3">
          <input
            type="email"
            placeholder="Enter your email"
            class="flex-1 px-5 py-3 rounded-full bg-gray-100 outline-none"
          />

          <button
            class="px-6 py-3 rounded-full bg-orange-500 text-white font-semibold"
          >
            Let’s Talk →
          </button>
        </div>
      </div>
    </div>
  </section>

  <section
    class="2xl:max-w-7xl xl:max-w-6xl lg:max-w-5xl md:max-w-3xl max-w-xl mx-auto px-4 space-y-10 bg-white rounded-lg shadow-md min-h-screen my-3"
  ></section>
</template>
