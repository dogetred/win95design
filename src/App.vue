<template>
  <div>
    <desktop />
  </div>
</template>

<script setup lang="ts">
import Desktop from "./view/desktop.vue";
import { useHead } from "@vueuse/head";

useHead({
  title: "aptxayc's personal computer",
  link: [
    {
      rel: "icon",
      href: "/favicon.ico",
    },
  ],
  meta: [
    { name: 'description', content: 'software engineer with expertise in both back-end, ML and low-level programming.' },
  ],
});
</script>
