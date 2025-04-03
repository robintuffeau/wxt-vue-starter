<script lang="ts" setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1 class="text-2xl font-bold text-center mb-4">{{ msg }}</h1>

  <div class="p-4 bg-white rounded-lg shadow-md max-w-md mx-auto mb-4">
    <button 
      type="button" 
      @click="count++" 
      class="px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600 transition-colors"
    >
      count is {{ count }}
    </button>
    <p class="mt-4">
      Edit
      <code class="bg-gray-100 px-1 rounded">components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p class="text-center mb-2">
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank" class="text-blue-500 hover:underline">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="text-center text-gray-500">Click on the WXT and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
