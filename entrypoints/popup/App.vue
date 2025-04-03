<script lang="ts" setup>
import HelloWorld from '@/components/HelloWorld.vue';
</script>

<template>
  <div class="flex justify-center space-x-4 p-4">
    <h1>WXT + Vue</h1>
    <a href="https://wxt.dev" target="_blank">
      <img src="/wxt.svg" class="logo h-24 p-6 transition-all hover:drop-shadow-lg" alt="WXT logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="@/assets/vue.svg" class="logo vue h-24 p-6 transition-all hover:drop-shadow-lg" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="WXT + Vue" />
</template>

<style scoped>
.logo:hover {
  filter: drop-shadow(0 0 2em #54bc4ae0);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
