<style>
@import 'tailwindcss';
@import '@nuxt/ui';

.rotate-enter-active,
.rotate-leave-active {
  transition: opacity 0.3s ease;
}

.rotate-enter-from,
.rotate-leave-to {
  opacity: 0;
}
</style>

<template>
  <NuxtPage />
</template>
