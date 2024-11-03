<script setup lang="ts">
const items = [
  'https://picsum.photos/640/640?random=0',
  'https://picsum.photos/640/640?random=1',
  'https://picsum.photos/640/640?random=2',
  'https://picsum.photos/640/640?random=3',
]
</script>

<template>
  <main>
    <ULink to="/other">other page</ULink>
    <UCarousel v-slot="{ item }" :items="items" dots loop autoplay>
      <img :src="item" width="320" height="320" class="rounded-lg" />
    </UCarousel>
  </main>
</template>
