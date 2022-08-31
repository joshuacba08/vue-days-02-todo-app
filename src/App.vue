<template>
  <div class="min-h-screen bg-slate-800">
    <Header />
    <TaskContainer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import TaskContainer from "./components/TaskContainer.vue";


export default {
  name: 'App',
  components: {
    Header,
    TaskContainer
}
}
</script>

<style>

</style>
