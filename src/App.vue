<script setup>
import { ref } from 'vue';
const name = ref("rishi")
const vue = ref("VUE.js")
const emogi = ref("🫡")
const year = ref("2026")
</script>

<template>

<header>
{{ emogi }}
</header>

<h1>Heloo {{ name }} </h1>
<p> am about to learn {{ vue }}!</p>

<footer>
  <p><span>@copy</span>:{{ year }}</p>
</footer>

</template>

<style scoped>
header {
  text-align: center;
  font-size: 3rem;
}

h1,p{
  text-align: center;
}

span {
  color: blue;
}
</style>
