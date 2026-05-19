<script>
import SiteHeader from './components/SiteHeader.vue'

export default {
  components: {
    SiteHeader
  },
  data() {
    return {
      count: 0
    }
  }
}


</script>


<template>
  <SiteHeader />
  <RouterView />
</template>

<style scoped>
main {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-content: center;
  text-align: center;
  font-family: system-ui, sans-serif;
  }


h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

</style>

<style>
body{
  background-color: #fafafa;
  font-family: Garamond, "Times New Roman", serif

}</style>
