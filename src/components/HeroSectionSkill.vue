<template>
  <section
    class="hero-section bg-white text-gray-800 py-20 h-screen flex items-center justify-center"
  >
    <div class="container mx-auto grid items-center justify-center text-center">
      <!-- First column -->
      <h1 class="text-6xl md:text-4xl font-bold mb-4">Skill</h1>
      <p class="text-lg md:text-xl mb-8">
        The skills, tools, and technologies I am proficient in.
      </p>
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-4">
        <SkillCard
          v-for="(item, index) in Skills"
          :key="index"
          :title="item.title"
          :img-src="item.imgSrc"
        />
      </div>
    </div>
  </section>
</template>

<script>
import SkillCard from './SkillCard.vue';

export default {
  name: 'HeroSectionSkill',
  components: {
    SkillCard,
  },
  data() {
    return {
      Skills: [
        {
          title: 'JavaScript',
          imgSrc:
            'https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg',
        },
        {
          title: 'TypeScript',
          imgSrc:
            'https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg',
        },
        {
          title: 'React.js',
          imgSrc:
            'https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg',
        },
        {
          title: 'Next.js',
          imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg',
        },
        {
          title: 'Vue.js',
          imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/9/95/Vue.js_Logo_2.svg',
        },
        {
          title: 'Adonis.js',
          imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/7/70/Tabler-icons_brand-adonis-js.svg',
        },
        {
          title: 'Tailwindcss',
          imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/d/d5/Tailwind_CSS_Logo.svg',
        },
        {
          title: 'Robot Framework',
          imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/e/e4/Robot-framework-logo.png',
        },
        {
          title: 'Playwright',
          imgSrc: 'https://sergej.codes/images/stack/tech/playwright.svg',
        },
        {
          title: 'Github',
          imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/c/c2/GitHub_Invertocat_Logo.svg',
        },
      ],
    };
  },
};
</script>

<style scoped>
/* Additional styles specific to HeroSection.vue */
.hero-section {
  /* Customize hero section styles here */
}
</style>
