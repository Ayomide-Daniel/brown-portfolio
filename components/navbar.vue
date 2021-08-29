<template>
  <div class="nav">
    <nav class="container">
      <a href=""><h2 class="bi bi-house"></h2></a>
      <a href=""><h2 class="bi bi-lightbulb"></h2></a>
      <a href=""><h2 class="bi bi-briefcase"></h2></a>
      <a href=""><h2 class="bi bi-telephone"></h2></a>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style scoped>
.nav {
  width: 100vw;
  z-index: 1;
}
nav {
  display: flex;
  justify-content: space-between;
}
nav a {
  padding: 1rem;
  margin: 0 0.5rem;
  color: #fff;
}
</style>
