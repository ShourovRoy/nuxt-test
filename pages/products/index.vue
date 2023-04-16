<template>
  <div>
    <NuxtClientFallback>
      <h1>Products</h1>
      <NuxtPage />
      <template #fallback="{ error }">
        You can display the error locally here.
      </template>
    </NuxtClientFallback>
  </div>
</template>
