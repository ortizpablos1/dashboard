<template>
  <div class="home">
    <HeaderComponent />
    <section>
      <p>
        CONTENIDO DE LA PAGINA <br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex itaque esse,
        iusto nobis asperiores nisi voluptatum a earum enim reprehenderit?
        Expedita voluptas voluptate quasi distinctio sint saepe velit eveniet
        minima.
      </p>
    </section>
    <FooterComponent />
  </div>
</template>

<script>
// @ is an alias to /src

import FooterComponent from "@/components/FooterComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";

export default {
  name: "HomeView",
  components: {
    FooterComponent,
    HeaderComponent,
  },
};
</script>
