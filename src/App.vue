<template>
  <Suspense>
    <div class="w-full h-screen" id="app">
      <navbar />
      <RouterView />
    </div>
  </Suspense>
</template>

<script setup lang="ts"></script>

<style scoped>
#app {
  text-align: center;
  color: #2c3e50;
}
</style>
