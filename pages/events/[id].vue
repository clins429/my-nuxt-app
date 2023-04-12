<script setup>
const route = useRoute()
console.log('params', route.params)
// const nuxt = useNuxtApp() // holds the app context
</script>

<template>
  <div>event id: {{ $route.params.id }}</div>
</template>
