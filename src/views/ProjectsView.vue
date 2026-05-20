<template>
  <main>
    <h1>Things I've Done</h1>
    <ProjectCard title="Solar System Simulation" description="details forthcoming" src="/solarsystem.png"
      altText="solar system" url="https://github.com/Ryanjones0911/UTD-Graphics-Final-Project" />
  </main>
</template>

<script setup lang="ts">
import ProjectCard from '@/components/ProjectCard.vue';
</script>

<style scoped>
main {
  display: grid;
  place-content: center;
  text-align: center;
  min-height: 30vh;
  max-width: 850px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 3rem;
  gap: 1.5rem;
}
</style>
