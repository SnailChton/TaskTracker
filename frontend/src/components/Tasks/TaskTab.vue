<script setup lang="ts">

import TaskList from "@/components/Tasks/TaskList.vue";
</script>

<template>
  <div class="right-sidebar">
    <div class="right-sidebar-header">
      <div class="notifications-btn"></div>
      <div class="profile"></div>
    </div>
    <div class="right-sidebar-categories">
      <div class="tasks-btn"></div>
      <div class="files-btn"></div>
    </div>
    <div class="tasks">
      <div class="tasks-statuses">
        <div class="active"></div>
        <div class="confirmed"></div>
        <div class="deleted"></div>
      </div>
      <TaskList/>
    </div>
  </div>
</template>

<style scoped>

</style>