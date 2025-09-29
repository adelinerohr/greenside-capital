<script setup lang="ts">
useHead({
  meta: [{ name: "viewport", content: "width=device-width, initial-scale=1" }],
  link: [{ rel: "icon", href: "/favicon.ico" }],
  htmlAttrs: {
    lang: "en",
  },
});

useSeoMeta({
  ogImage: "https://ui.nuxt.com/assets/templates/nuxt/landing-light.png",
  twitterImage: "https://ui.nuxt.com/assets/templates/nuxt/landing-light.png",
  twitterCard: "summary_large_image",
});
</script>

<template>
  <UApp :toaster="{ expand: false }">
    <UMain>
      <NuxtPage />
    </UMain>
  </UApp>
</template>
