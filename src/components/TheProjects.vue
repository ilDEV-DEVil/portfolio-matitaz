<script setup lang="ts">
  import BaseProject from './BaseProject.vue';
</script>

<template>
  <div class="projects" id="projects">
    <div class="main-project">
      <BaseProject name="Project 1"/>
    </div>
    <div class="minor-projects">
      <BaseProject name="Project 2"/>
      <BaseProject name="Project 3"/>
      <BaseProject name="Project 4"/>
    </div>
  </div>
</template>

<style scoped lang="scss">
.projects {
  padding: 1rem;

  .main-project {
    height: 500px;
    width: 100%;
  }

  .minor-projects {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 500px;
    gap: 16px 16px;
    grid-template-areas:
      ". . .";
    justify-items: stretch;
    margin-top: 16px;
  }
}
</style>
