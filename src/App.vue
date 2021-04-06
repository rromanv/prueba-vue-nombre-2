<template>
  <h1>Hola {{ nombre }}</h1>
</template>

<script setup>
import { ref } from 'vue'

const nombre = ref('Rodolfo Roman')
</script>
