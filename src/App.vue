<template>
    <div id="app" class="container">
        <div class="todo-wrapper">
            <todo-header></todo-header>
            <div class="todo-content">
                <todo-report></todo-report>
                <todo-list></todo-list>
            </div>
        </div>
    </div>
</template>
<script>
    import TodoHeader from './components/TodoHeader.vue';
    import TodoReport from './components/TodoReport.vue';
    import TodoList from './components/TodoList.vue';
    // 引用组件

    export default {
        components: {
            TodoHeader,
            TodoReport,
            TodoList
        }
    }
</script>
<style lang="stylus">

</style>