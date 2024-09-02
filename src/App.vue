<script setup>
import ToDoItem from './components/ToDoItem.vue'
</script>

<template>
  <div id="app">
    <h1>To-Do List</h1>
    <ul>
      <li>
        <to-do-item label="My Todo List"></to-do-item>
      </li>
    </ul>
  </div>
</template>
