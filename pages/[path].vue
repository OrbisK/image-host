<template>
  <img :src="`${route.params.path}.png`" style="width: 100%; max-height: 99vh" />
</template>

<script setup lang="ts">
const route = useRoute()

</script>