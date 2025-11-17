<template>
  <div>
    <Preloader />
    <Navbar />
    <div class="d-flex">
      <main class="flex-grow-1">
        <HomePage />
        <ServicesPage />
        <ProjectsPage />
        <SkillsSection />
        <ContactSection />
      </main>
    </div>
    <SiteFooter />
  </div>
</template>

<script setup>
import ContactSection from './components/ContactSection.vue';
import Navbar from './components/Navbar.vue';
import Preloader from './components/Preloader.vue';
import Sidebar from './components/Sidebar.vue';
import SiteFooter from './components/SiteFooter.vue';
import HomePage from './components/pages/HomePage.vue';
import ProjectsPage from './components/pages/ProjectsPage.vue';
import ServicesPage from './components/pages/ServicesPage.vue';
import SkillsSection from './components/SkillsSection.vue';
</script>
