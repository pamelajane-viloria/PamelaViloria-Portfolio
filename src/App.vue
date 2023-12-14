<template>
  <div id="app">
    <AppHeader />
    <HeroSection />
    <AboutSection />
    <ProjectsSection />
    <ContactSection />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from '@/components/Header.vue';
import HeroSection from '@/components/Hero.vue';
import AboutSection from '@/components/About.vue';
import ProjectsSection from '@/components/Projects.vue';
import ContactSection from '@/components/Contact.vue';
import AppFooter from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    HeroSection,
    AboutSection,
    ProjectsSection,
    ContactSection,
    AppFooter
  }
}
</script>

<style>
@import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";
#app {
  font-family: 'Montserrat', sans-serif;  
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #e5e5e5;
}
</style>
