<script setup>
import headerpage from '@/components/headerpage.vue'
import { RouterLink, RouterView } from 'vue-router'
import footerpage from '../src/components/footerpage.vue'
</script>

<template>
  <headerpage/>
  <RouterView />
  <footerpage/>
</template>

<style scoped>

</style>
