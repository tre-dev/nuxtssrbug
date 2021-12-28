<template>
  <div style="display: flex; flex-flow: row">
    <div>above Nuxt</div>
    <Nuxt style="flex: 1" />
    <div>below Nuxt</div>
  </div>
</template>

<style scoped>
img {
  position: fixed;
  top: 20px;
  right: 20px;
  z-index: 1000;
}
</style>
