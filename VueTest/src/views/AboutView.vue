<template>
  <div class="bg-gray-50 min-h-screen">
    <Header />
    <main class="container mx-auto p-6">
      <WhoWeAreSection />
      <OurVisionSection />
      <PlaceholderImage />
      <AboutFeaturesSection />
      <WorkWithUsSection />
    </main>
    <Footer />
  </div>
</template>


<script>
import Header from '../components/Header.vue';
import WhoWeAreSection from '../components/WhoWeAreSection.vue';
import OurVisionSection from '../components/OurVisionSection.vue';
import PlaceholderImage from '../components/PlaceholderImage.vue';
import AboutFeaturesSection from '../components/AboutFeaturesSection.vue';
import WorkWithUsSection from '../components/WorkWithUsSection.vue';
import Footer from '../components/Footer.vue';

export default {
  components: {
    Header,
    WhoWeAreSection,
    OurVisionSection,
    PlaceholderImage,
    AboutFeaturesSection,
    WorkWithUsSection,
    Footer,
  },
};
</script>
