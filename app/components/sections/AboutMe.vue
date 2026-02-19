<script setup lang="ts"></script>

<template>
  <section class="container-app mt-12">
    <div
      class="bg-white rounded-[3rem] shadow-md p-10 grid grid-cols-1 md:grid-cols-2 gap-10"
    >
      <!-- LEFT: STORY -->
      <div class="space-y-5">
        <h2 class="text-3xl font-bold">My Story ✨</h2>

        <p class="text-gray-600 leading-relaxed">
          Hey! I’m <span class="font-semibold">Haiza</span>, a Fullstack
          Developer who started with a strong focus on backend development using
          Laravel.
        </p>

        <p class="text-gray-600 leading-relaxed">
          Over time, I began exploring the frontend world with Nuxt.js and
          discovered how exciting it is to bring ideas to life through clean and
          responsive user interfaces.
        </p>

        <p class="text-gray-600 leading-relaxed">
          Right now, I’m also learning Flutter to build cross-platform mobile
          apps — step by step, project by project.
        </p>

        <p class="text-gray-600 leading-relaxed">
          I enjoy building real-world applications, improving my skills every
          day, and turning simple concepts into useful digital products 🚀
        </p>
      </div>

      <!-- RIGHT: HIGHLIGHTS -->
      <div class="space-y-6">
        <h3 class="text-2xl font-semibold">What I’m Working On 💡</h3>

        <ul class="space-y-4 text-gray-700">
          <li class="flex items-start gap-3">
            <span class="text-orange-500 text-xl">✔</span>
            Building scalable backend APIs with Laravel
          </li>

          <li class="flex items-start gap-3">
            <span class="text-orange-500 text-xl">✔</span>
            Creating responsive UI with Nuxt + Tailwind CSS
          </li>

          <li class="flex items-start gap-3">
            <span class="text-orange-500 text-xl">✔</span>
            Learning Flutter to ship modern mobile apps
          </li>

          <li class="flex items-start gap-3">
            <span class="text-orange-500 text-xl">✔</span>
            Growing into a strong and reliable Fullstack Developer
          </li>
        </ul>

        <!-- Small Quote -->
        <div class="bg-gray-100 rounded-2xl p-5 text-gray-600 italic">
          “I believe consistency beats speed — progress comes one step at a
          time.”
        </div>
      </div>
    </div>
  </section>
</template>
