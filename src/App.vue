<template>

<!-- Content -->
    <div class="px-3 py-10 md:px-10">
        <div class="w-full sm:w-1/2 lg:w-1/3 mx-auto">
            <TodoSpinner/>
            <TodoFormAdd/>
            <TodoItems/>
            <!-- Todo empty -->
            <div class="text-center text-lg text-gray-500">
                Você ainda não tem nenhuma tarefa.
            </div>
            <!--/ Todo empty -->
        </div>
    </div>
    <!--/ Content -->


</template>

<script>

import TodoSpinner from "@/components/TodoSpinner";
import TodoFormAdd from "@/components/TodoFormAdd";
export default {
  name: 'App',
  components: {
    TodoFormAdd,
    TodoSpinner

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
