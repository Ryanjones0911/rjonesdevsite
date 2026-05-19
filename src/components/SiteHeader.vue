<template>
  <header>


    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/projects">Projects</RouterLink>
      <RouterLink to="/blog">Blog</RouterLink>
    </nav>
  </header>
</template>

<style scoped>
header {
  position: relative;
  display: flex;
  align-items: center;
  padding: 1.25rem 2.5rem;
  border-bottom: 1px solid #e5e5e5;
  border-radius: .75rem;
  background-color: #f5f5f5;
}

nav {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  gap: 1.75rem;
}

a {
  color: #333;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.5s ease, transform 0.5s ease;
}

a:hover {
  color: #306ed1;
  transform: scale(1.153);
}
</style>
