<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="wrapper">
    <nav>
      <RouterLink to="/davictavionnavaire">Davictavionnavaire</RouterLink>
      <!-- <RouterLink to="/about">About</RouterLink> -->
    </nav>
  </div>
  <RouterView />
</template>

<style lang="scss" scoped></style>
