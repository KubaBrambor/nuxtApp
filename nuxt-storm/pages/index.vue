<template>
  <div>
    <header>
      <nav>
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
      </nav>
    </header>
    <h1>Home Page</h1>
    <h4>{{ text }}</h4>
  </div>
</template>

<script setup lang="ts">
  const text: string = 'Brainstorm session'
</script>

<style scoped>

</style>