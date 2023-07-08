<script setup lang="ts">
const props = defineProps(['to']);
</script>

<template>
  <NuxtLink :to="props.to" class="border-b hover:bg-pink-900 p-1"><slot/></NuxtLink>
</template>

<style scoped>

</style>