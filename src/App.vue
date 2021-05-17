<template>
  <todo-app-builder></todo-app-builder>
</template>

<script>
    import TodoAppBuilder from './pages/TodoAppBuilder/TodoAppBuilder.vue';

    export default {
        components: {
            TodoAppBuilder
        }
    }
</script>


<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>
