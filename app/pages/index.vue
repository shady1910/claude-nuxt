<template>
  <div>
    <NuxtRouteAnnouncer />
    <h1>Title</h1>
    <AppButton>Button</AppButton>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Resume',
  meta: [
    { name: 'description', content: 'My amazing site.' },
  ],
  bodyAttrs: {
    class: 'test',
  },
  script: [{ innerHTML: 'console.log(\'Hello world\')' }],
}),
useSeoMeta({
  title: 'Mein CV',
  ogTitle: 'My Amazing Site',
  description: 'This is my amazing site, let me tell you all about it.',
  ogDescription: 'This is my amazing site, let me tell you all about it.',
  ogImage: 'https://example.com/image.png',
  twitterCard: 'summary_large_image',
})
</script>

<style>

</style> 