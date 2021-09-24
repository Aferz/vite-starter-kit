<template>
  <p class="text-2xl text-gray-700">
    {{ $props.message }}
  </p>
</template>

<script setup lang="ts">
defineProps<{
  message: string
}>()
</script>
