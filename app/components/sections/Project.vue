<script setup lang="ts">
const projects = [
  {
    title: "Laravel REST API",
    desc: "A scalable backend API with authentication and clean architecture.",
    stack: ["Laravel", "MySQL", "JWT"],
  },
  {
    title: "Nuxt Portfolio Website",
    desc: "A modern personal portfolio built with Nuxt and Tailwind CSS.",
    stack: ["Nuxt", "Tailwind"],
  },
  {
    title: "Flutter Mobile App",
    desc: "Cross-platform mobile application for real-world business needs.",
    stack: ["Flutter", "Firebase"],
  },
];
</script>

<template>
  <section class="container-app mt-12">
    <div class="bg-white rounded-[3rem] shadow-md p-10 space-y-10">
      <!-- Title -->
      <div class="text-center space-y-3">
        <h2 class="text-3xl font-bold">Projects 🚀</h2>
        <p class="text-gray-500">
          Some of the projects I’ve built while learning and growing as a
          Fullstack Developer.
        </p>
      </div>

      <!-- Projects Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div
          v-for="project in projects"
          :key="project.title"
          class="p-7 rounded-3xl bg-gray-50 hover:shadow-lg transition space-y-5"
        >
          <!-- Project Title -->
          <h3 class="text-xl font-semibold">
            {{ project.title }}
          </h3>

          <!-- Description -->
          <p class="text-gray-600 text-sm leading-relaxed">
            {{ project.desc }}
          </p>

          <!-- Stack Badges -->
          <div class="flex flex-wrap gap-2">
            <span
              v-for="tech in project.stack"
              :key="tech"
              class="px-3 py-1 text-xs rounded-full bg-white border text-gray-600"
            >
              {{ tech }}
            </span>
          </div>

          <!-- Button -->
          <button
            class="mt-3 text-sm font-semibold text-orange-500 hover:text-orange-600 transition"
          >
            View Details →
          </button>
        </div>
      </div>
    </div>
  </section>
</template>
