<script setup>
import { ref } from 'vue'
const name = ref('rishi')
const vue = ref('VUE.js')
</script>

<template>
  <h1>
    Helloo <span>{{ name }}</span>
  </h1>

  <p>I am about to learn {{ vue }}!</p>
</template>

<!-- scoped means only this template css will apply -->
<style scoped>
header span {
  font-size: 3rem;
}

h1,
p {
  display: block;
  text-align: center;
}

h1 > span {
  color: aqua;
  text-decoration: underline;
  text-transform: capitalize;
  font-weight: 500;
  font-family:
    system-ui,
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    'Open Sans',
    'Helvetica Neue',
    sans-serif;
}
</style>
