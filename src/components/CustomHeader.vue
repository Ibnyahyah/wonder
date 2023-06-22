<script setup lang="ts">
import StarIcon from '@/components/icons/starIcon.vue'
</script>

<template>
    <marquee behavior="alternate" scroll-amount="20" direction="left" scroll-delay="10">
      <div class="marquees">
        <div class="maquee_element">
          <h1>Welcome to wonder portfolio</h1>
          <StarIcon />
        </div>
        <div class="maquee_element">
          <h1>Welcome to wonder portfolio</h1>
          <StarIcon />
        </div>
        <div class="maquee_element">
          <h1>Welcome to wonder portfolio</h1>
          <StarIcon />
        </div>
        <div class="maquee_element">
          <h1>Welcome to wonder portfolio</h1>
          <StarIcon />
        </div>
      </div>
    </marquee>
</template>

<style scoped>
marquee{
  border-top: 2px solid var(--secondary-color);
  border-bottom: 2px solid var(--secondary-color);
  margin: 20px 0;
}
.marquees{
  padding: 10px 0;
  display: flex;
  align-items: center;
  gap: 20px;
}
.maquee_element {
  display: flex;
  align-items: center;
  gap: 20px;
}
</style>
