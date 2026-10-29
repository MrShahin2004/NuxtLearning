<template>
  <main>
    <h1>{{ Message }}</h1>

    <p>This is the second page.</p>
  </main>
</template>

<script setup>
import { ref } from "vue";

const Message = ref("Yo!");
</script>

<style scoped></style>
