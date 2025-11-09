<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="text-2xl">Test for DaisyUI</div>

  <div class="badge badge-accent">Badge for DaisyUI</div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
