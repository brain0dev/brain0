<script setup lang="ts">

</script>

<template>
  <div class="p-4 font-semibold">
    <NavigationBar/>
    <div class="flex justify-center items-center flex-row font-mono">
      <div>
        <div class="mr-20 title-slogan manifold">
          <p>{{ $t('title1') }} </p>
          <p>{{ $t('title2') }}</p>
        </div>
        <div class="flex flex-row mt-12 ml-1 text-2xl font-medium">
          <NuxtLink to="/library" class="n-button-base mr-20">{{ $t('get_started') }}</NuxtLink>
          <NuxtLink to="/about" class="n-button-base">Learn More</NuxtLink>
        </div>
      </div>
      <img src="public/brain0.transparent.png" class="logo" alt="Brain0 icon">
    </div>
  </div>
</template>

<style scoped>

</style>