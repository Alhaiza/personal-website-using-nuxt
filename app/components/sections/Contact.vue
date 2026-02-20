<script setup lang="ts"></script>

<template>
  <section class="container-app mt-12">
    <div
      class="bg-white rounded-[3rem] shadow-md p-10 grid grid-cols-1 md:grid-cols-2 gap-10"
    >
      <!-- LEFT: INFO -->
      <div class="space-y-6">
        <h2 class="text-3xl font-bold">Contact Me 📩</h2>

        <p class="text-gray-500 leading-relaxed">
          Have a project idea, collaboration, or just want to say hi? Feel free
          to reach out — I’d love to connect with you!
        </p>

        <!-- Contact Details -->
        <div class="space-y-4 text-gray-700">
          <p class="flex items-center gap-3">
            <span class="text-orange-500 text-xl">📧</span>
            alqadrihaiza@gmail.com
          </p>

          <p class="flex items-center gap-3">
            <span class="text-orange-500 text-xl">📞</span>
            +62 895-6182-04842
          </p>

          <p class="flex items-center gap-3">
            <span class="text-orange-500 text-xl">📍</span>
            Indonesia
          </p>
        </div>

        <!-- Quote -->
        <div class="bg-gray-100 rounded-2xl p-5 italic text-gray-600">
          “Let’s build something meaningful together 🚀”
        </div>
      </div>

      <!-- RIGHT: FORM -->
      <div class="space-y-5">
        <h3 class="text-2xl font-semibold">Send a Message</h3>

        <form class="space-y-4">
          <!-- Name -->
          <input
            type="text"
            placeholder="Your Name"
            class="w-full px-5 py-3 rounded-2xl bg-gray-100 outline-none focus:ring-2 focus:ring-orange-400"
          />

          <!-- Email -->
          <input
            type="email"
            placeholder="Your Email"
            class="w-full px-5 py-3 rounded-2xl bg-gray-100 outline-none focus:ring-2 focus:ring-orange-400"
          />

          <!-- Message -->
          <textarea
            rows="4"
            placeholder="Your Message..."
            class="w-full px-5 py-3 rounded-2xl bg-gray-100 outline-none focus:ring-2 focus:ring-orange-400"
          ></textarea>

          <!-- Button -->
          <button
            type="submit"
            class="w-full py-3 rounded-full bg-orange-500 text-white font-semibold hover:bg-orange-600 transition"
          >
            Send Message →
          </button>
        </form>
      </div>
    </div>
  </section>
</template>
