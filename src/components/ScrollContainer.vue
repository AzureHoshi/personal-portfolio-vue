<template>
  <div class="snap-y snap-mandatory h-screen overflow-y-scroll">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'ScrollContainer',
};
</script>

<style>
.snap-y {
  scroll-snap-type: y mandatory;
}
</style>
