<template>
  <header class="bg-blue-500 text-white py-4 w-full">
    <div class="flex justify-between items-center px-8">
      <h1 class="text-lg font-bold">My Website</h1>
      <nav class="space-x-4">
        <router-link to="/" class="hover:underline">Go to Home</router-link>
        <router-link to="/about" class="hover:underline">Go to About</router-link>
      </nav>
    </div>
  </header>
</template>

