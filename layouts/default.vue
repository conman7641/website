<!-- layouts/default.vue -->
<template>
    <div>
      <!-- Global navigation bar -->
      <header class="bg-gray-900 py-4">
        <!-- Navigation links -->
        <nav class="flex justify-center">
          <nuxt-link to="/" exact active-class="border-b-2 border-white px-4 py-2 text-white" class="px-4 py-2 text-white">Home</nuxt-link>
          <nuxt-link to="/about" active-class="border-b-2 border-white px-4 py-2 text-white" class="px-4 py-2 text-white">About</nuxt-link>
          <!-- Add more navigation links as needed -->
        </nav>
      </header>
      
      <!-- Page content -->
      <main>
        <nuxt />
      </main>
    </div>
  </template>
  