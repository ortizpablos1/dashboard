<template>
  <div class="padre">
    <img src="@/assets/logo.png" alt="Logo Pagina" width="50px" />
    <h1>TIENDA DEPORTIVA</h1>
    <nav class="menu">
      <li><router-link to="/">Inicio</router-link></li>
      <li><router-link to="/about">Nosotros</router-link></li>
      <li><router-link to="/contacto">Contacto</router-link></li>
      <li><router-link to="/dashboard">Dashboard</router-link></li>
    </nav>
  </div>
</template>

<script>
export default {
  name: "HeaderConponent",
};
</script>

<style scoped>
.padre {
  background-color: aqua;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.menu {
  width: 30%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
a {
  text-decoration: none;
}
li {
  list-style: none;
}
</style>