<script setup>
import { ref } from 'vue'

const year = ref('2026')
</script>

<template>
  <footer>
    <p>&copy; : {{ year }}</p>
  </footer>
</template>

<style scoped>
p {
  left: 50%;
  position: fixed;
  bottom: 0;
  padding-bottom: 40px;
}
</style>
