<template>
  <div class="about">
    <HeaderComponent />
    <h1>CONTENIDO DE LA PAGINA</h1>
    <p>
      NOSOTROS <br />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit eius vitae ex
      quasi, deserunt ipsam nisi excepturi voluptatem impedit incidunt alias
      aspernatur eum ea velit rerum corporis commodi delectus! Odio.
    </p>

    <FooterComponent />
  </div>
</template>
<script>
import HeaderComponent from "@/components/HeaderComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";
export default {
  name: "AboutView",
  components: {
    FooterComponent,
    HeaderComponent,
  },
};
</script>
