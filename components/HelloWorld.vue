<script lang="ts" setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="bg-white rounded-lg shadow-md p-6">
    <h1 class="text-2xl font-bold text-center text-gray-800 mb-6">{{ msg }}</h1>

    <div class="flex flex-col items-center mb-6">
      <button 
        type="button" 
        @click="count++" 
        class="px-5 py-2.5 bg-blue-500 text-white font-medium rounded-lg hover:bg-blue-600 focus:ring-4 focus:ring-blue-300 transition-colors"
      >
        count is {{ count }}
      </button>
      
      <p class="mt-4 text-gray-600">
        Edit
        <code class="bg-gray-100 px-2 py-0.5 rounded text-sm font-mono">components/HelloWorld.vue</code> 
        to test HMR
      </p>
    </div>

    <div class="text-center space-y-2">
      <p class="text-gray-700">
        Install
        <a 
          href="https://github.com/vuejs/language-tools" 
          target="_blank" 
          class="text-blue-600 hover:text-blue-800 font-medium hover:underline"
        >
          Volar
        </a>
        in your IDE for a better DX
      </p>
      
      <p class="text-gray-500 text-sm">
        Click on the WXT and Vue logos to learn more
      </p>
    </div>
  </div>
</template>
