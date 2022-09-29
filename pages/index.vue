<script setup>
import { ref, onMounted } from "vue";
const el = ref();

onMounted(() => {
  console.log(el.value);
});
</script>

<template>
  <div ref="el">home</div>
</template>
