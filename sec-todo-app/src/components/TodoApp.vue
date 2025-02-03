<script setup>
import TodoFormVue from "./TodoForm.vue";
import TodoListVue from "./TodoList.vue";

</script>

<template>
    <div class="todo-app">
        <h1>To Do App</h1>
        <TodoFormVue/>
        <TodoListVue/>
    </div>
</template>

<style scoped>
.todo-app{
    padding: 5vh;
    min-height: 100vh;
    width: 30vw;
    background-color: #f7f9fc;

}

</style>