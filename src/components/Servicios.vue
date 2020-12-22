<template>
  <v-container my-16>
    <v-row>
      <v-col v-for="(art) of datos" :key="art.id">
        <v-card class="col-lg-6 col-xs-12 border x-auto" max-width="344">
          <v-img
            :src="art.codigo"
            height="200px"
          ></v-img>

          <v-card-title> {{ art.nombre }} </v-card-title>

          <v-card-subtitle> {{ art.descripcion }} </v-card-subtitle>

          <v-card-actions>
            <v-btn color="orange lighten-2" text> Explore </v-btn>

            <v-spacer></v-spacer>

            <v-btn icon @click="show = !show">
              <v-icon>{{
                show ? "mdi-chevron-up" : "mdi-chevron-down"
              }}</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>




<script>
import axios from "axios";
export default {
  data() {
    return {
      datos: null,
    };
  },
  mounted() {
    axios.get("articulo/list").then((response) => (this.datos = response.data));
  },
};
</script>