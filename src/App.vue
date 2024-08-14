<template>
  <Navbar :logo="logo_src" :alt="app_name" />
  <router-view />
  <Footer />
</template>

<script>
import Footer from './components/Footer.vue'
import Navbar from './components/Navbar.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
  },
  data() {
    return {
      app_name: 'Fabio Vige',
      logo_src: require('@/assets/logo.png'),
    }
  },
}
</script>

<style>
</style>
