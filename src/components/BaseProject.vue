<script setup lang="ts">
  defineProps(['name'])
</script>

<template>
  <div class="project">
    {{ name }}
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
      transition: transform 200ms;
      &:hover {
        transform: scale(0.95)
      }
    }
</style>
