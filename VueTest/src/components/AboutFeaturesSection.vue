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
        { title: 'Innovation', description: 'We focus on bringing innovative ideas to life, ensuring that each project we take on has the potential to push boundaries and create lasting impact.' },
        { title: 'Collaboration', description: 'We value teamwork and believe that great things happen when teams come together to share knowledge and expertise.' },
        { title: 'Integrity', description: 'Integrity is at the heart of everything we do. We believe in building trust with our clients and partners through honesty and transparency.' },
      ],
    };
  },
};
</script>
   