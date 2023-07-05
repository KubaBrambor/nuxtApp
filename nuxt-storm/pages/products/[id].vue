<template>
  <div>
    <p>Product details for {{ id }}</p>
  </div>
</template>

<script setup lang="ts">
  definePageMeta({
    layout: 'products'
  })
  const { id } = useRoute().params
</script>

<style scoped>

</style>