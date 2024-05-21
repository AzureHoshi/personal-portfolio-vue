<template>
  <div class="p-4 rounded flex flex-col justify-center items-center">
  <img
    v-if="imgSrc"
    :src="imgSrc"
    :alt="title"
    class="h-16 mx-auto mb-4"
  />
  <h2 class="text-2xl font-semibold mb-2">{{ title }}</h2>
</div>

</template>

<script>
export default {
  name: 'SkillCard',
  props: {
    title: String,
    imgSrc: String,
  },
};
</script>

<style scoped>
/* Additional styles specific to CardComponent.vue */
</style>
