<template>
  <div class="nav">
    <nav class="container">
      <a href="#home"><h2 class="bi bi-house"></h2></a>
      <a href="#motivation"><h2 class="bi bi-lightbulb"></h2></a>
      <a href="#jobs"><h2 class="bi bi-briefcase"></h2> </a>
      <a href="#contact"><h2 class="bi bi-telephone"></h2></a>
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
  padding: 1rem;
  justify-content: space-between;
}
nav a {
  /* padding: 1rem; */
  margin: 0 0.25rem;
  color: #fff;
  display: block;
  text-align: center;
  text-decoration: none;
  font-weight: 600;
  text-transform: uppercase;
}
</style>
