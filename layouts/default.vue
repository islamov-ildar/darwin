<script setup lang="ts">
  console.log('loaded123');
</script>

<template>
  <section class="grid" style="height: 100vh">
    <LayoutSideBar />
    <div>
      <slot />
    </div>
  </section>
</template>

<style scoped>
.grid {
  display: grid;
  grid-template-columns: 1fr 6fr;
}
</style>