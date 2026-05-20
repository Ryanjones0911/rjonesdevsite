<template>
  <div class='project-card'>
    <h2 class='title'>{{ title }}</h2>
    <img :src="src" :alt="altText">
    <p>{{ description }}</p>
    <a :href="url" target="_blank">Github</a>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  title: string
  description: string
  src: string
  altText: string
  url: string
  ghTitle: string
}>()




</script>



<style scoped>
.project-card {
  padding: 1.5rem 1.6rem;
  margin-bottom: 1.25rem;
  border: 1px solid #e1e1e1;
  border-radius: 1rem;
  background-color: #f8f8f8;

}
</style>
