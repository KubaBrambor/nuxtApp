<template>
  <div class="card text-center flex flex-col justify-between">
    <img :src="product.image" :alt="product.title" class="thumb h-[400px]">
    <p class="font-bold text-gray-500 m-4 truncate">{{ product.title }}</p>
    <NuxtLink :to="`/products/${product.id}`">
      <p class="btn my-4">View Details</p>
    </NuxtLink>
  </div>
</template>

<script setup lang="ts">
  const { product } = defineProps(['product'])
</script>

<style scoped>

</style>