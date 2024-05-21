<template>
  <div id="app md:min-h-screen">
    <Navbar />
    <HeroSection />
    <HeroSectionAbout />
    <HeroSectionSkill />
    <footer class="bg-gray-800 text-white text-center p-4">
      © 2024 My Website
    </footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import ScrollContainer from './components/ScrollContainer.vue';
import Section from './components/Section.vue';
import HeroSection from './components/HeroSection.vue';
import HeroSectionAbout from './components/HeroSectionAbout.vue';
import HeroSectionSkill from './components/HeroSectionSkill.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    ScrollContainer,
    Section,
    HeroSection,
    HeroSectionAbout,
    HeroSectionSkill,
  },
};
</script>

<style>
@media (max-width: 768px) {
  /* ปรับขนาดหรือสไตล์ต่าง ๆ ขององค์ประกอบในหน้าจอขนาดเล็กกว่า md ตามต้องการ */
}
</style>
