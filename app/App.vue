<template>
  <div id="body">
    <main>
      <h1>My {{ framework }} Journey</h1>

      <p>Lessons completed: {{ lessonsCompleted }}</p>

      <button @click="lessonsCompleted++">Complete another lesson</button>
    </main>
  </div>
</template>

<script setup>
import { ref } from "vue";

const framework = ref("Nuxt 4");
const lessonsCompleted = ref(1);
</script>

<style>
#body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
