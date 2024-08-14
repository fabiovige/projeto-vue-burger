<template>
  <nav>
    <router-link to="/">
      <img :src="logo" :alt="alt" id="logo" />
    </router-link>
    | <router-link to="/">Home</router-link> |
    <router-link to="/about">Sobre</router-link> |
    <router-link to="/contact">Contato</router-link>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  props: ['logo', 'alt'],
}
</script>

<style>
nav {
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 10px;
}

#logo {
  height: 50px;
}

router-link {
  color: white;
  text-decoration: none;
  padding: 0 10px; /* Espaçamento entre os links */
}

router-link:hover {
  text-decoration: underline;
}
</style>