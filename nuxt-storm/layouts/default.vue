<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt Brainstorm</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <div>
      <!-- output the page content -->
      <slot />
    </div>
  </div>
</template>

<style scoped>
  .router-link-exact-active {
    color: aquamarine;
  }
</style>