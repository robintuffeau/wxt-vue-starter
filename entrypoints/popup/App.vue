<script lang="ts" setup>
import HelloWorld from '@/components/HelloWorld.vue';
</script>

<template>
  <div class="max-w-md mx-auto p-6 bg-gray-50 min-h-screen">
    <div class="flex items-center justify-center gap-6 mb-8">
      <a href="https://wxt.dev" target="_blank" class="block">
        <img src="/wxt.svg" class="h-16 transition-all hover:scale-110 hover:drop-shadow-lg" alt="WXT logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank" class="block">
        <img src="@/assets/vue.svg" class="h-16 transition-all hover:scale-110 hover:drop-shadow-lg" alt="Vue logo" />
      </a>
    </div>
    <HelloWorld msg="WXT + Vue" />
  </div>
</template>

<style>
body {
  @apply bg-gray-50 text-gray-900;
  margin: 0;
}
</style>
