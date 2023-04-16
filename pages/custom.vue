<script setup>
definePageMeta({ layout: 'custom' })
const { sayHello } = useUtils()
sayHello()
</script>

<template>
  <div>custom page</div>
</template>
