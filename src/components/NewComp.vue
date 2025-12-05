<template>
  <div class="card">
    <h2>{{ title }}</h2>
    <p>{{ message }}</p>
    <button @click="handleClick">Click Me</button>
  </div>
</template>

<script setup>
import { ref } from "vue";

// Local reactive data
const count = ref(0);

// Props (values passed from parent)
defineProps({
  title: {
    type: String,
    default: "Default Title",
  },
  message: {
    type: String,
    default: "This is a basic Vue component."
  }
});

// Methods
function handleClick() {
  count.value++;
  alert(`Button clicked ${count.value} times`);
}
</script>

<style scoped>
.card {
  border: 1px solid #aaa;
  padding: 1rem;
  border-radius: 10px;
  width: 280px;
}
button {
  margin-top: 10px;
  cursor: pointer;
  padding: 6px 12px;
}
</style>
