<script setup>
defineOptions({
  name: 'DefaultLayout',
})
</script>

<template>
  <div>
    <the-header />
    <main
      id="#main-content"
      style="margin-top: 3rem"
    >
      <slot />
    </main>
  </div>
</template>

<style lang="scss">
</style>
