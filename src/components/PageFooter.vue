<template>
  <footer>
    Copyright &copy; {{ currentYear }} ATBSPB. All rights reserved.
  </footer>
</template>

<script setup>
import { ref } from 'vue'

const currentYear = ref(new Date().getFullYear())
</script>
