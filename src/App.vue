<script setup>
  const name = "Vue 3";
  const active = null;
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <h2 v-if="active === true">Estoy en true</h2>
  <h2 v-else-if="active === false">Estoy en false</h2>
  <p>Lorem ipsum dolor sit</p>
  <h2 v-else>Estoy indeciso</h2>
</template>

