<template>
  <NuxtPage />
</template>

<script setup>

useHead({
  htmlAttrs: { lang: "en" },
  title: "Kane - Personal Portfolio",
  meta: [
    {
      name: "viewport",
      content: "width=device-width, initial-scale=1",
    },
    { charset: "utf-8" },
    {
      name: "description",
      content:
        "Portfolio of Kane - Fullstack Developer, expert in Nuxt 4 and Laravel.",
    },
    { property: "og:title", content: "Kane - Personal Portfolio" },
    { property: "og:type", content: "website" },
  ],
  link: [
    { rel: "icon", type: "image/png", href: "/images/favicon.png" },
    { rel: "shortcut icon", type: "image/png", href: "/images/favicon.png" },
  ],
});
</script>

