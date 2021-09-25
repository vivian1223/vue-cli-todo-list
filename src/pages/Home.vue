<template>
    <div class="bg-info vh-100 p-5">
        <div class="container">
            <div class="row justify-content-center">
                <h1 class="bg-primary col-4 text-center py-3 mb-3 text-white rounded">
                紀錄你的習慣日常
            </h1>
            </div>
            <TodoList></TodoList>
        </div>
    </div>
</template>

<script>
import TodoList from '@/components/TodoList.vue';

export default {
  name: 'Home',
  components: {
    TodoList,
  },
};
</script>
