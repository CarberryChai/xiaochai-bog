<script lang="ts" setup>
import siteConfig from '../site-config'
</script>

<template>
  <footer class="w-full px-6 pt-4 pb-12 max-w-3xl mx-auto opacity-60">
    <div class="flex flex-wrap justify-center text-dark dark:text-white">
      <span class="opacity-70">2023-{{ new Date().getFullYear() }} ©</span>
      <a class="!nav-link opacity-100 ml-1" href="/">{{ siteConfig.author }}</a>
    </div>
  </footer>
</template>
