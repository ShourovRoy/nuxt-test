<template>
  <div>
    <h1>Product</h1>
    <p>{{ id }}</p>
  </div>
</template>

<script setup lang="ts">
const route = useRoute();

const id = ref(route.params.id);
throw createError("Product not found");
</script>
