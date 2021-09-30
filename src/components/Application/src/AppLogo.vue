<template>
  <div>{{ count }}</div>
  <button @click="add">click me</button>
</template>

<script setup lang="ts">
  import { ref } from 'vue';
  const count = ref(1);
  function add() {
    count.value++;
  }
</script>
