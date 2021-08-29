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
  backdrop-filter: blur(4px);
  background: rgba(0, 0, 0, 0.25);
}
</style>
