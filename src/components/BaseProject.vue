<script setup lang="ts">
  defineProps(['name'])
</script>

<template>
  <div class="project">
    <div class="project-name">
      {{ name }}
    </div>
  </div>
</template>

<style scoped lang="scss">
  .project {
      height: 100%;
      width: 100%;
      border: 1px solid darkgray;
      border-radius: 8px;
      font-size: 2rem;
      font-weight: lighter;
      color: black;
      padding: 1rem 2rem;
      display: flex;
      align-items: end;
      background-image: url("../assets/images/matitaz.jpeg");
      background-position: center;
      background-size: cover;
      cursor: pointer;
      transition: transform 200ms;

      &:hover {
        transform: scale(0.95);
      }

      &-name {
        background-color: white;
        border-radius: 8px;
        padding: 0 4px;
        line-height: 1.3;
      }
    }
</style>
