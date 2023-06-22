<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import CustomHeader from './components/CustomHeader.vue';
</script>

<template>
  <div>
    <CustomHeader />
    <!-- <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/project">Project</RouterLink>
    </nav> -->
    <div class="container">
    <RouterView />
    </div>
  </div>
</template>

<style scoped>
div.container{
  width: 85%;
  margin: 0 auto;
  max-width: 1440px;
}
</style>
