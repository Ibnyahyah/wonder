
<template>

</template>

<script  lang="ts">
import wonder from '@/components/icons/wonder.vue'
export default {
    name: 'Card',
    props:{
        children: HTMLElement,
    }
}
</script>

<style scoped>
.row {
  display: flex;
  align-items: center;
  gap: 10px;
}
.card {
  background: var(--linear-color);
  border: 2.5px solid #393939;
  border-radius: 20px;
  width: 31.4%;
  padding: 10px;
  height: 200px;
}
.card:last-child {
  width: calc(31.4% * 2);
}
.card p:first-child {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: 500;
  line-height: 22px;
  letter-spacing: 0em;
  text-align: left;
}
.card h2 {
  margin: 5px 0;
  font-size: 20px;
  font-weight: 700;
  line-height: 32px;
  letter-spacing: 0em;
  text-align: left;
}
.card p:last-child {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: 500;
  line-height: 17px;
  letter-spacing: 0em;
  text-align: left;
}
</style>
