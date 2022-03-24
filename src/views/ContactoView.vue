<template>
  <div>
    <HeaderComponent />

    <h1>Contactate con Nosotros</h1>

    <FooterComponent />
  </div>
</template>

<script>
import FooterComponent from "@/components/FooterComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
export default {
  name: "ContactoView",
  components: {
    FooterComponent,
    HeaderComponent,
  },
};
</script>

<style scoped>
h1 {
  background-color: rgb(3, 157, 246);
  color: aliceblue;
}
</style>