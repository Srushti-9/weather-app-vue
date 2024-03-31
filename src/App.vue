<script setup>
import { RouterView } from 'vue-router';
import SiteNavigation from './components/SiteNavigation.vue';
</script>

<template>
  
    <div class="flex flex-column min-h-screen font-Roboto bg-weather-primary">
      <SiteNavigation/>
      <RouterView/>
    </div>

  
</template>

<style lang="scss" scoped>

</style>
