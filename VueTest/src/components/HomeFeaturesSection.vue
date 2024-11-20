<template>
    <section class="py-16">
      <h2 class="text-3xl font-bold text-center mb-8">Features</h2>
      <div class="flex justify-center gap-8">
        <div v-for="feature in features" :key="feature.title" class="bg-blue-100 p-4 rounded shadow-md">
          <h3 class="text-xl font-bold">{{ feature.title }}</h3>
          <p class="text-gray-600">{{ feature.description }}</p>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        features: [
          { title: 'Feature 1', description: 'Detailed description of feature 1.' },
          { title: 'Feature 2', description: 'Detailed description of feature 2.' },
          { title: 'Feature 3', description: 'Detailed description of feature 3.' },
        ],
      };
    },
  };
  </script>
   