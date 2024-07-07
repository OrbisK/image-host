<template>
  <img :src="`${route.params.path}.PNG`" style="width: 100%; max-height: 99vh" />
</template>

<script setup lang="ts">
const route = useRoute()

</script>