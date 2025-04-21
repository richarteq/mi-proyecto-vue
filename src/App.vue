<script setup>
  const name = "Vue 3";
  const styleColor = "color: red;";
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <h2 v-bind:style="styleColor">Hola {{ name }}</h2>
</template>