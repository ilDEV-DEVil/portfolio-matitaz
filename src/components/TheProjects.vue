<script setup lang="ts"></script>

<template>
  <div class="projects" id="projects">
    <div class="main-project"></div>
      <div class="minor-projects">
        <div class="project">
          project 1
        </div>
        <div class="project"></div>
        <div class="project"></div>
      </div>
  </div>
</template>

<style scoped lang="scss">
.projects {
  padding: 1rem;

  .main-project {
    height: 500px;
    width: 100%;
    border: 1px solid darkgray;
    border-radius: 8px;
    transition: transform 200ms;
      &:hover {
        transform: scale(0.95)
      }
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

    .project {
      border: 1px solid darkgray;
      border-radius: 8px;
      font-size: 2rem;
      font-weight: lighter;
      color: black;
      padding: 1rem 2rem;
      display: flex;
      align-items: end;
      transition: transform 200ms;
      &:hover {
        transform: scale(0.95)
      }
    }
  }
}
</style>
