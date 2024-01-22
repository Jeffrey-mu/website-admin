<script setup>
import { layout } from '@/composables/setting'
import Layout from './components/Layout.vue'
definePageMeta({
  layout: layout,
})
</script>
<template>
  <Layout>
    <div>finance-1</div>
    <a v-for="item in 10" :href="`details/${item}`">{{ item }}</a>
  </Layout>

</template>
