<script setup>
import { ref } from 'vue'

// reactive value
const count = ref(0)
</script>

<template>
  <p>In-DOM Root Component Template-D1</p>
  <button @click="count++">{{ count }}</button>
</template>

<style scoped></style>
