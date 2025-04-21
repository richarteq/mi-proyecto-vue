<script setup>
  const name = "Vue 3";
  const active = true;
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <h2 v-show="active">Estoy en true</h2>
</template>

