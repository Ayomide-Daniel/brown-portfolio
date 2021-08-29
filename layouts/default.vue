<template>
  <v-app>
    <Navbar class="navbar-component" />
    <v-main>
      <Nuxt />
    </v-main>
    <!-- <v-footer>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer> -->
  </v-app>
</template>

<script>
import Navbar from '~/components/navbar.vue'
export default {
  components: { Navbar },
  data() {
    return {}
  },
}
</script>

<style scoped>
.navbar-component {
  position: fixed;
  width: 100vw;
  bottom: 0;
  right: 0;
  left: 0;
  margin: 0 auto;
  z-index: 10;
  backdrop-filter: blur(5px);
  background: rgba(125, 125, 125, 0.5);
}
</style>
