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
@import url('https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400..800;1,400..800&display=swap');

main {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-content: center;
  text-align: center;
  font-family: EB Garamond, serif;
}


h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}
</style>

<style>
body {
  background-color: #fafafa;
  font-family: EB Garamond, "Times New Roman", serif
}
</style>
