<script setup lang="ts">
import {version} from '../package.json'
</script>

<template>
  <footer class="shrink-0 h-6">
    <div class="text-center text-xs font-light">
      {{ version }} | 更多精彩
      <a href="https://lyone.xyz" target="_blank"
         class="text-neutral-500 hover:text-neutral-900 underline dark:text-neutral-400 dark:hover:text-neutral-300">GitHub</a>
    </div>
  </footer>
</template>