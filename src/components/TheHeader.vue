<script setup>

</script>

<template>
  <header>
    <h1 class="logo">LikeIm</h1>
    <nav>
      <ul class="links-container">
        <li><a href="#home">Home</a></li>
        <li><a href="#likes">Likes</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  background: hsl(60, 80%, 70%);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
}

.logo {
  font-size: 1rem;
  color: #333;
}

.links-container {
  list-style-type: none;
  display: flex;
  font-size: 0.8rem;
}

a {
  text-decoration: none;
  display: inline-block;
  /* background: #666; */
  padding: 0.5rem;
  color: #444;
  font-size: 0.6rem;
}

a:hover {
  box-shadow: 0 2px 0 #444;
}

</style>
