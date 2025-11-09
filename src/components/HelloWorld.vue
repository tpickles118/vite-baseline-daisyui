<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button class="btn btn-sm btn-primary" @click="count++">
      count is {{ count }}
    </button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <div class="badge badge-accent">Badge for DaisyUI</div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
