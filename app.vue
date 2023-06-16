<template>
  <div>
    <NuxtWelcome />
  </div>
</template>
<script setup lang="ts">
import { useRoute, useRuntimeConfig, useLazyAsyncData, useAsyncData, useSeoMeta, useHead, useServerSeoMeta } from '#imports';

useServerSeoMeta({
  title: 'A title',
  description: 'A description',
  canonical: 'https://tubular-taffy-de4720.netlify.app/',
  lang: 'en',
  ogImage: 'https://res.cloudinary.com/klandestino-ab/image/upload/c_fill,w_1200,h_630,q_auto,f_auto/djurensratt-se/loggor/share_1200x630',
  ogUrl: 'https://tubular-taffy-de4720.netlify.app/',
  twitterCard: 'summary_large_image',
  twitterImage: 'https://res.cloudinary.com/klandestino-ab/image/upload/c_fill,w_1200,h_630,q_auto,f_auto/djurensratt-se/loggor/share_1200x630',
  abstract: 'A description',
  ogTitle: 'A title',
  ogDescription: 'A description',
  ogType: 'website',
  twitterTitle: 'A title',
  twitterDescription: 'A description',
  twitterUrl: 'https://tubular-taffy-de4720.netlify.app/',
  twitterSite: '@example',
  robots: 'index,follow',
});

</script>
