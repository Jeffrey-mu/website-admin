<script setup>
import { layout } from '@/composables/setting'
definePageMeta({
  layout: layout,
})
const route = useRoute()
const name = route.params.id
</script>
<template>
  <div>{{ name }}</div>
</template>
