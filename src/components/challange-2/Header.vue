<script setup>
import { ref } from 'vue'
const title = ref('Vue')
</script>

<template>
  <h1>
   Hi, i'am <span>{{ title }}</span>
  </h1>
</template>


<style scoped >
h1{
  font-size: 2rem;
  color: #1d1d1d;
}

h1 > span {
  color: rgb(130, 255, 130);
}
</style>
