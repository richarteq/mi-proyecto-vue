<script setup>
  const name = "Vue 3";

  const fruta = {
    name: "Naranja",
    price: "$3.00",
    description: "Una naranja",
  };
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <ul>
    <li v-for="(value, propiedad) in fruta">
      {{ propiedad }} : {{ value }}
    </li>
  </ul>
</template>

