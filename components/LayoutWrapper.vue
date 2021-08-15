<template>
  <div class="wrapper">
    <slot />
  </div>
</template>
<script>
export default {
  name: 'LayoutWrapper',
}
</script>
<style scoped>
.wrapper {
  padding-top: 80px;
  @media (min-width: 769px) {
    padding-top: 0;
  }
}
</style>
