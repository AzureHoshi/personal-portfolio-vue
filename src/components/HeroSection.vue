<template>
  <section
    class="hero-section bg-white text-gray-800 py-20 h-screen flex items-center justify-center p-4 sm:pt-60 md:pt-0"
  >
    <div
      class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-4 items-center justify-center text-center"
    >
      <div class="md:col-span-1 relative">
        <h1 class="text-5xl md:text-6xl font-bold mb-4">Hello, I'm P</h1>
        <h2 class="text-3xl md:text-4xl font-semibold mb-4">
          Junior Web Developer
        </h2>
        <p class="text-lg md:text-xl mb-8">
          I specialize in building websites and web applications that are
          accessible, responsive, and performant.
        </p>
      </div>
      <div class="md:col-span-1 flex justify-center md:justify-end relative">
        <!-- รูปภาพ -->
        <div class="relative">
          <img
            src="../assets/ImgProfile.webp"
            alt="Arnut Kamsuwan"
            class="rounded w-64 h-64 md:w-96 md:h-96 shadow-lg relative z-30 object-cover mx-auto"
          />
          <!-- เพิ่มรูปสี่เหลี่ยมซ้อนที่ตำแหน่งที่ต้องการ -->
          <div
            class="absolute bottom-0 right-0 transform translate-x-6 translate-y-6"
            style="z-index: 20"
          >
            <div class="bg-gray-600 w-64 h-64 md:w-96 md:h-96"></div>
          </div>
          <!-- สิ้นสุดการเพิ่มรูปสี่เหลี่ยมซ้อน -->
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
};
</script>

<style scoped>
/* Additional styles specific to HeroSection.vue */
.hero-section {
  /* Customize hero section styles here */
}
</style>
