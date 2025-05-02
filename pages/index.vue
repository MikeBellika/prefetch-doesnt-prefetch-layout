<template>
  <div>
    Hello world! <br />
    <NuxtLink
      to="my-page-with-two-cols"
      prefetch
      prefetched-class="prefetched"
      prefetch-on="interaction"
      >Two columns!</NuxtLink
    ><br />
    <NuxtLink
      to="my-page"
      prefetch
      prefetched-class="prefetched"
      prefetch-on="interaction"
      >My layout!</NuxtLink
    >
  </div>
</template>
<style>
.prefetched {
  color: red;
}
</style>
