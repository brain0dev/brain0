<script setup lang="ts">

</script>

<template>
  <div class="bg-black text-white p-4 font-semibold">
    <NavigationBar/>
    <div class="flex justify-center items-center flex-row font-mono">
      <div>
        <div class="mr-20 title manifold">
          <p>{{ $t('title1') }} </p>
          <p>{{ $t('title2') }}</p>
        </div>
        <div class="flex flex-row mt-12 ml-1 text-2xl font-medium">
          <a href="/library" class="n-button-base mr-20">{{ $t('get_started') }}</a>
          <a href="/about" class="n-button-base">Learn More</a>
        </div>
      </div>
      <img src="public/brain0.transparent.png" class="logo" alt="Brain0 icon">
    </div>
  </div>
</template>

<style scoped>

</style>