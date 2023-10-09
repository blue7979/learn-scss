<script lang="ts" setup>
useHead({
  link: [
    {
      rel: "preconnect",
      href: "https://fonts.googleapis.com"
    },
    {
      rel: "preconnect",
      href: "https://fonts.gstatic.com",
      crossorigin: "anonymous",
    },
    {
      rel: "stylesheet",
      href: "https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Lato:wght@400;700&display=swap",
      value: {

      }
    }
  ],
  title: "Chef site"
})
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

