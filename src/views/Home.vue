<template>
  <div class="home">
    <Barra />
    <Descripcion />


    <Carousel />
    <Servicios />

    <Testimonios />
    <!-- <Team /> -->
  </div>
</template>


<script>
// @ is an alias to /src
import Barra from "@/components/Barra.vue";
import Carousel from "@/components/Carousel.vue";
import Descripcion from "@/components/Descripcion.vue";
import Testimonios from "@/components/Testimonios.vue";
// import Team from "@/components/Team.vue";
import Servicios from "@/components/Servicios.vue";

export default {
  name: "Home",
  components: {
    Barra,
    Carousel,
    Descripcion,
    Testimonios,
    // Team,
    Servicios,
  }
};
</script>
