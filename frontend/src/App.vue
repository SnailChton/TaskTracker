<script setup lang="ts">
import {RouterLink, RouterView} from 'vue-router'
import TaskItem from "@/components/Tasks/TaskItem.vue";
import ProjectDepartment from "@/components/Projects/ProjectDepartment.vue";
import FastSearch from "@/components/Search/FastSearch.vue";
import TaskList from "@/components/Tasks/TaskList.vue";
import ContactList from "@/components/Contacts/ContactList.vue";
import ProjectTab from "@/components/Projects/ProjectTab.vue";
import ContactTab from "@/components/Contacts/ContactTab.vue";
import LeftSidebarHeader from "@/components/LeftSidebarHeader.vue";
import CenterHeader from "@/components/CenterHeader.vue";
import MessageField from "@/components/MessageField.vue";
import CenterSubHeader from "@/components/CenterSubHeader.vue";
import RightSidebarHeader from "@/components/RightSidebarHeader.vue";
import RightSidebarSubHeader from "@/components/RightSidebarSubHeader.vue";
</script>

<template>
  <header>
  </header>
  <body>
    <div class="left-sidebar">
      <LeftSidebarHeader/>
      <ContactTab/>
      <ProjectTab/>
    </div>
    <div class="content">
      <CenterHeader/>
      <CenterSubHeader/>
      <div class="content-main-tab">
        <MessageField/>
      </div>
    </div>
  <div class="right-sidebar">
    <RightSidebarHeader/>
    <RightSidebarSubHeader/>
  </div>
  </body>
  <!--  <header>-->
  <!--    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />-->

  <!--    <div class="wrapper">-->
  <!--      <HelloWorld msg="You did it!" />-->

  <!--      <nav>-->
  <!--        <RouterLink to="/">Home</RouterLink>-->
  <!--        <RouterLink to="/about">About</RouterLink>-->
  <!--      </nav>-->
  <!--    </div>-->
  <!--  </header>-->

  <!--  <RouterView />-->
</template>

<style scoped>
</style>
