<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <h1 class="scss1">Nuxt Routing set up successfully!</h1>
    <p>Current route: {{ route.path }}</p>
    <a href="https://nuxt.com/docs/getting-started/routing" target="_blank">Learn more about Nuxt Routing</a>
    <img src="/favicon.ico" alt="Discover Nuxt 3" />
    <NuxtLink to="/about">关于</NuxtLink>
  </div>
</template>

<style >


</style>
