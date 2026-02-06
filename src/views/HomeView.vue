<script setup lang="ts">
import TheProjects from '../components/TheProjects.vue';
import TheHero from '../components/TheHero.vue';
import TheFooter from '../components/TheFooter.vue';

</script>

<template>
  <main>
    <TheHero/>
    <TheProjects/>
    <TheFooter/>
  </main>
</template>

<style scoped>
main {
  background-color: white;
}
</style>
