<template>
  <section class="text-center py-16 bg-white w-full px-6">
    <h2 class="text-3xl font-bold mb-4 text-blue-500">Meet Our Team</h2>
    <p class="text-gray-600 mb-8">
      Our team is a mix of talented individuals who bring unique skills and perspectives to the table.
    </p>
    <div class="flex justify-center gap-8">
      <div class="text-center">
        <div class="bg-gray-300 rounded-full w-40 h-40 mb-4"></div>
        <h3 class="text-lg font-semibold">John Doe</h3>
        <p class="text-gray-500">Lead Developer</p>
      </div>
      <div class="text-center">
        <div class="bg-gray-300 rounded-full w-40 h-40 mb-4"></div>
        <h3 class="text-lg font-semibold">Jane Smith</h3>
        <p class="text-gray-500">UI/UX Designer</p>
      </div>
      <div class="text-center">
        <div class="bg-gray-300 rounded-full w-40 h-40 mb-4"></div>
        <h3 class="text-lg font-semibold">Samuel Lee</h3>
        <p class="text-gray-500">Product Manager</p>
      </div>
    </div>
  </section>
</template>


  
  <script>
  export default {
    data() {
      return {
        team: [
          { name: 'John Doe', role: 'Lead Developer' },
          { name: 'Jane Smith', role: 'UI/UX Designer' },
          { name: 'Samuel Lee', role: 'Product Manager' },
        ],
      };
    },
  };
  </script>
  