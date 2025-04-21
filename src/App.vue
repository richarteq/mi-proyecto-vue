<script setup>
  const name = "Vue 3";
  const arrayFrutas = [
    {
      name: "Manzana",
      price: "$1.00",
      description: "Una manzana",
    },
    {
      name: "Pera",
      price: "$2.00",
      description: "Una pera",
    },
    {
      name: "Naranja",
      price: "$3.00",
      description: "Una naranja",
    },
  ];
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <ul>
    <li v-for="fruta in arrayFrutas" :key="name">
      {{ fruta.name }} - {{ fruta.price }} - {{ fruta.description }}
    </li>
  </ul>
</template>

