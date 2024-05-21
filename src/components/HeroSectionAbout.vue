<template>
  <section
    class="hero-section bg-gray-100 text-gray-800 py-20 h-screen flex items-center justify-center"
  >
    <div class="container mx-auto grid items-center justify-center text-center">
      <!-- First column -->
      <div class="col-span-1">
        <h1 class="text-6xl md:text-4xl font-bold mb-4">About</h1>
        <p class="text-lg md:text-xl mb-8">
          I specialize in building websites and web applications that are
          accessible, responsive, and performant.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSectionAbout',
};
</script>

<style scoped>
/* Additional styles specific to HeroSection.vue */
.hero-section {
  /* Customize hero section styles here */
}
</style>
