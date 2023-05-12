<script setup>
import Todo from '../components/Todo.vue'
</script>
<template>
  <main>
    <div class="todo">
      <h1>This is an Todo page</h1>
      <Todo />
    </div>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .todo {
    min-height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
}
</style>
