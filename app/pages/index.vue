<template>
  <div></div> <!-- optional, nothing will show since we're redirecting -->
</template>

<script setup>
import { onMounted } from 'vue';

onMounted(() => {
  window.location.href = 'https://jadenstock.com';
});
</script>
