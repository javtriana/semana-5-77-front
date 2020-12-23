<template>
  <v-container>
    <v-row class="d-flex justify-space-between">
      <v-col max-height="150">
        <v-hover v-slot="{ hover }" light>
          <v-card
            :elevation="hover ? 4 : 2"
            class="mx-auto"
            height="300"
            max-width="350"
          >
            <v-container>
              <v-row class="d-flex justify-center mt-2">
                <v-icon size="60px" color="rgba(8,126,223,1)"
                  >mdi-cube</v-icon
                >
              </v-row>

              <v-row class="d-flex justify-center mt-5">
                <p class="font-weight-bold headline text--white">
                   Para productos   
                </p>
              </v-row>

              <v-row class="d-flex justify-center mt-2">
                <p class=" subtitle-1 text--white ma-3">
                  Estimación de la vida útil de sus productos, desarrollando modelos de ultima generación
                </p>
              </v-row>
            </v-container>
          </v-card>
        </v-hover>
      </v-col>

      <v-col max-height="150">
        <v-hover v-slot="{ hover }" light>
          <v-card
            :elevation="hover ? 4 : 2"
            class="mx-auto"
            height="300"
            max-width="350"
          >
            <v-container>
              <v-row class="d-flex justify-center mt-2">
                <v-icon size="60px" color="rgba(8,126,223,1)"
                  >mdi-face-agent</v-icon
                >
              </v-row>

              <v-row class="d-flex justify-center mt-5">
                <p class="font-weight-bold headline text--white">
                  Para servicios
                </p>
              </v-row>

              <v-row class="d-flex justify-center mt-3">
                <p class=" subtitle-1 text--white ma-3">
                  Desarrollando nuevas herramientas para realizar estudios predictivos, <br/>buscando la optimización de los servicios.
                </p>
              </v-row>
            </v-container>
          </v-card>
        </v-hover>
      </v-col>

      <v-col max-height="150">
        <v-hover v-slot="{ hover }" light>
          <v-card
            :elevation="hover ? 4 : 2"
            class="mx-auto"
            height="300"
            max-width="350"
          >
            <v-container>
              <v-row class="d-flex justify-center mt-2">
                <v-icon size="60px" color="rgba(8,126,223,1)"
                  >mdi-account-multiple-plus</v-icon
                >
              </v-row>

              <v-row class="d-flex justify-center mt-5">
                <p class="font-weight-bold headline text--white">
                  Para marketing
                </p>
              </v-row>

              <v-row class="d-flex justify-center mt-3">
                <p class=" subtitle-1 text--white ma-3">
                  Aplicados al comportamiento de clientes e  <br/> identificación de clientes potenciales
                </p>
              </v-row>
            </v-container>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
  </v-container>
</template>


<script>
export default {
  data() {
    return {};
  }
};
</script>