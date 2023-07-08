<script setup lang="ts">

</script>

<template>
  <div class="p-4 font-semibold">
    <NavigationBar/>
    <div class="flex justify-center items-center flex-row font-mono">
      <div>
        <div class="mr-20 text-[90px] font-bold manifold">
          <p>{{ $t('title1') }} </p>
          <p>{{ $t('title2') }}</p>
        </div>
        <div class="flex flex-row mt-12 ml-1 text-2xl font-medium">
          <CoolButton to="/library" class="mr-20">{{ $t('get_started') }}</CoolButton>
          <CoolButton to="/about">Learn More</CoolButton>
        </div>
      </div>
      <img src="public/brain0.transparent.png" class="logo" alt="Brain0 icon">
    </div>
  </div>
</template>

<style scoped>
.manifold {
  background: -webkit-linear-gradient(#eee 0%, #444 50%, #f65b74 51%, #f72078 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.logo {
  image-rendering: pixelated;
  width: 500px;
  height: 500px;
  filter: brightness(90%);
}
</style>