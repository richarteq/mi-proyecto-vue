<script setup>
  const name = "Vue 3";
  const active = false;
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <h2 v-if="active">v-if en acción</h2>
  <h2 v-else>v-else en acción</h2>
</template>