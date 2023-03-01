<template>
  <!-- your component template here -->
  <h1>{{ message }}</h1>
</template>

<script setup>
import { ref } from 'vue';

const message = ref('This is a compiled vue component');
</script>

<style scoped>
/* your component styles here */
</style>
