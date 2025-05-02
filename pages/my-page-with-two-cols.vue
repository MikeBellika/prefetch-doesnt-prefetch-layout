<script setup lang="ts">
definePageMeta({
  layout: false,
});
</script>
<template>
  <NuxtLayout name="two-columns">
    <div>Hello world!</div>
    <template #right> I'm on the right </template>
  </NuxtLayout>
</template>
