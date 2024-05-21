<template>
  <section
    class="snap-start flex justify-center items-center"
    :class="bgColor"
  >
    <slot></slot>
  </section>
</template>

<script>
export default {
  props: ['bgColor'],
};
</script>

<style scoped>
.snap-start {
  scroll-snap-align: start;
  height: 100vh;
}
</style>
