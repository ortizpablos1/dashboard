<template>
  <div>
    <nav>
      <li><router-link to="/usuario"> Fotografia</router-link></li>
      <li><router-link to="/datos"> Datos Personales</router-link></li>
      <li><router-link to="/experiencia"> Experiencia</router-link></li>
    </nav>
  </div>
</template>
<script>
export default {
  name: "SidebarComponent",
};
</script>
<style scoped>
li {
  list-style: none;
  text-align: start;
}
</style>