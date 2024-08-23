<script setup>
import { ref } from 'vue'
const text = ref(0)
</script>

<template>
  <main>
    <input v-model.number="text" />
  </main>
</template>

<style scoped></style>
