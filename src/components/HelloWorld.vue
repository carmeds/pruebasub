<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <p>Nuevos componentes desde git</p>
  </div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
