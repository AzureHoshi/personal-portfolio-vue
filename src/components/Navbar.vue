<template>
  <nav class="bg-gray-300 p-4">
    <div class="container mx-auto flex justify-between items-center">
      <div class="text-gray-900 text-lg font-Montserrat font-bold">
        Arnut Kamsuwan
      </div>
      <div
        class="md:flex space-x-4 text-gray-900 text-lg font-Montserrat font-bold"
      >
        <a
          href="#"
          class="hover:text-gray-300"
          >About</a
        >
        <a
          href="#"
          class="hover:text-gray-300"
          >Work</a
        >
        <a
          href="#"
          class="hover:text-gray-300"
          >Contact</a
        >
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    },
  },
};
</script>

<style scoped>
/* Add any additional styles if needed */
</style>
