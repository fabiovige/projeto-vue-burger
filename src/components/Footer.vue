<template>
  <footer>
    <p id="site-name">Fabio Vige</p>
    <p id="version">v0.0.1</p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style>
footer {
  display: flex;
  justify-content: space-between;
  padding: 10px 20px;
  background-color: #333;
  color: #d3d3d3; /* Cor do texto cinza claro */
  font-size: 14px;
  position: fixed;
  bottom: 0;
  left: 0;
  width: 98%;
}

#site-name,
#version {
  margin: 0;
}
</style>
