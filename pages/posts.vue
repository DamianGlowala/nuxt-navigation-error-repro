<template>
  <div>{{ data }}</div>
</template>

<script setup lang="ts">
const data = await useFetch("https://jsonplaceholder.typicode.com/posts");
</script>
