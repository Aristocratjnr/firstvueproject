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
    <button type="button" @click="count++">Click Me🥺: {{ count }}</button>
    <p>
      <code>My First Vue project</code> 
    </p><br />
    <footer><code>Aristocratjnr</code></footer>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
