<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div data-theme="business">
    <header class="navbar bg-base-300 flex justify-between">
      <h1 class="font-bold text-xl"><app-icon class="mr-2"></app-icon> A Website</h1>
      <div class="flex gap-1">
        <RouterLink class="btn btn-ghost" to="/">Home</RouterLink>
        <RouterLink class="btn btn-ghost" to="/about">About</RouterLink>
      </div>
    </header>
    <div class="p-2 container mx-auto bg-base-200">
      <RouterView />
    </div>
  </div>
</template>
