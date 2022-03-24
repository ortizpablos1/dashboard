<template>
  <div>
    <HeaderComponent />
    <section class="dahb">
      <SidebarComponent class="comp" />
      <div class="contenido">
        <router-view />
      </div>
    </section>
    <FooterComponent />
  </div>
</template>
<script>
import SidebarComponent from "@/components/SidebarComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";
export default {
  name: "DashboardView",
  components: {
    SidebarComponent,
    HeaderComponent,
    FooterComponent,
  },
};
</script>
<style scoped>
.dahb {
  display: flex;
}
.contenido {
  border: 1px solid green;
}
.comp {
  background-color: aliceblue;
}
</style>