<template>
  <div class="preloader" :class="{ loaded: isLoaded }">
    <div class="cssload-box-loading"></div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'

const isLoaded = ref(false)

onMounted(() => {
  setTimeout(() => {
    isLoaded.value = true
  }, 400)
})
</script>
