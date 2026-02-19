<script setup lang="ts">
import { ref } from 'vue'

const isOpen = ref(false)

const menuItems = [
  { name: 'Home', path: '#' },
  { name: 'About', path: '#' },
  { name: 'Contact', path: '#' },
]
</script>

<template>
  <nav class="fixed top-4 left-0 w-full z-50">
    <!-- Logo -->
    <div class="2xl:max-w-7xl xl:max-w-6xl lg:max-w-5xl md:max-w-3xl max-w-xl mx-auto bg-orange-600 text-white rounded-lg shadow-lg px-6 py-4 flex justify-between items-center">

      <h1 class="font-bold text-lg">LOGO</h1>
      <!-- Desktop Menu -->
      <ul class="hidden md:flex gap-8 font-medium">
        <li v-for="item in menuItems" :key="item.name" class="hover:text-gray-200">
          <NuxtLink :to="item.path">{{ item.name }}</NuxtLink>
        </li>
      </ul>

      <!-- Hamburger Mobile -->
      <button @click="isOpen = !isOpen" class="md:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none"
            viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>

        <!-- Mobile Menu -->
        <div
          v-if="isOpen"
          class="max-w-xl mx-auto mt-3 bg-orange-600 rounded-2xl
                px-6 py-4 flex flex-col gap-3 md:hidden shadow-lg"
        >
          <NuxtLink
            v-for="item in menuItems"
            :key="item.name"
            :to="item.path"
            @click="isOpen = false"
            class="text-white hover:text-gray-200"
          >
            {{ item.name }}
          </NuxtLink>
        </div>
    
  </nav>
</template>