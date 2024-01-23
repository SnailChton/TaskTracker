<script setup lang="ts">

import ProjectDepartment from "@/components/Projects/ProjectDepartment.vue";
</script>

<template>
  <div class="projects">
    <div class="project-header">
      <div class="title">
        <h3>Проекты</h3>
        <button class="add-new-project-btn">addNewProject</button>
      </div>
      <button class="projects-options">options</button>
    </div>
    <div class="my-tasks">Мои задачи</div>
    <div class="all-tasks-and-statistic">Все задачи и статистика</div>
    <div class="projects-content">
      <ProjectDepartment/>
    </div>
  </div>
</template>

<style scoped>

</style>