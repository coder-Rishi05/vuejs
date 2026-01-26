<script setup>
import { ref } from 'vue'
const emogi = ref('🫡')
</script>

<template>
  <header>
    <span>
      {{ emogi }}
    </span>
  </header>
</template>

<!-- scoped means only this template css will apply -->
<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: center;
  /* background-color: white; */
}

header span {
  font-size: 3rem;
  text-align: center;
  padding: 2rem 0;
  
}
</style>
