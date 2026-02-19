<script setup lang="ts"></script>

<template>
  <section class="container-app mt-12">
    <div class="bg-white rounded-[3rem] shadow-md p-10 space-y-10">
      <!-- Title -->
      <div class="text-center space-y-3">
        <h2 class="text-3xl font-bold">Services 💼</h2>
        <p class="text-gray-500">
          Here are the things I enjoy building and working on.
        </p>
      </div>

      <!-- Services Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Service 1 -->
        <div class="p-6 rounded-2xl bg-gray-50 hover:shadow-md transition">
          <h3 class="font-semibold text-lg mb-2">Backend APIs</h3>
          <p class="text-sm text-gray-600">
            Building secure and scalable REST APIs using Laravel and MySQL.
          </p>
        </div>

        <!-- Service 2 -->
        <div class="p-6 rounded-2xl bg-gray-50 hover:shadow-md transition">
          <h3 class="font-semibold text-lg mb-2">Frontend Web UI</h3>
          <p class="text-sm text-gray-600">
            Creating responsive and modern interfaces with Nuxt + Tailwind CSS.
          </p>
        </div>

        <!-- Service 3 -->
        <div class="p-6 rounded-2xl bg-gray-50 hover:shadow-md transition">
          <h3 class="font-semibold text-lg mb-2">Mobile Apps</h3>
          <p class="text-sm text-gray-600">
            Developing cross-platform mobile apps using Flutter.
          </p>
        </div>

        <!-- Service 4 -->
        <div class="p-6 rounded-2xl bg-gray-50 hover:shadow-md transition">
          <h3 class="font-semibold text-lg mb-2">Fullstack Solutions</h3>
          <p class="text-sm text-gray-600">
            Connecting frontend, backend, and database into real-world products.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
