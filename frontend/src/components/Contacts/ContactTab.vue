<script setup lang="ts">

import ContactList from "@/components/Contacts/ContactList.vue";
</script>

<template>
  <div class="contacts">
    <div class="title">
      <h3>Контакты</h3>
      <button class="add-new-contact-btn">addNewContact</button>
    </div>
    <ContactList/>
  </div>
</template>

<style scoped>

</style>