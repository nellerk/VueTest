<template>
  <div class="bg-gray-50 min-h-screen">
    <Header />
    <main class="container mx-auto p-6">
      <TeamSection />
      <PlaceholderImage />
      <ContactSection />
      <HomeFeaturesSection />
    </main>
    <Footer />
  </div>
</template>






<script>
import Header from '../components/Header.vue';
import TeamSection from '../components/TeamSection.vue';
import PlaceholderImage from '../components/PlaceholderImage.vue';
import ContactSection from '../components/ContactSection.vue';
import HomeFeaturesSection from '../components/HomeFeaturesSection.vue';
import Footer from '../components/Footer.vue';

export default {
  components: {
    Header,
    TeamSection,
    PlaceholderImage,
    ContactSection,
    HomeFeaturesSection,
    Footer,
  },
};
</script>
