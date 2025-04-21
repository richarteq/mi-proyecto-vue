<script setup>
  const name = "Vue 3";

  const handleClick = (message) => {
    console.log(message);
  };
</script>

<template>
  <h1>Hola {{ name }}!</h1>
  <button @click.right.prevent="handleClick('Mensaje desde botón')">
    Click right
  </button>
  <button @click.middle="handleClick('Mensaje desde botón')">
    Click middle
  </button>
</template>

