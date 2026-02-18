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
  <nav class="bg-gray-800 text-white px-4 py-3 flex justify-between items-center relative">
    <!-- Logo -->
    <div class="text-xl font-bold">LOGO</div>

    <!-- Desktop Menu -->
    <ul class="hidden md:flex space-x-6">
      <li v-for="item in menuItems" :key="item.name" class="hover:text-gray-300">
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

    <!-- Mobile Menu -->
    <ul v-if="isOpen" class="absolute top-12 left-0 w-full bg-gray-800 flex flex-col space-y-2 px-4 py-2 md:hidden">
      <li v-for="item in menuItems" :key="item.name">
        <NuxtLink :to="item.path" @click="isOpen = false" class="block py-2 hover:text-gray-300">
          {{ item.name }}
        </NuxtLink>
      </li>
    </ul>
  </nav>
</template>