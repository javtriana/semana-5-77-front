<template>

    <v-card max-height="500" tile>
      <v-img
        src="https://cdn.vuetifyjs.com/images/carousel/planet.jpg"
        gradient="to right, rgba(8,126,223,.75), rgba(1,66,182,1)"
        max-height="500"
        dark
      >
        <v-container fluid>
          <v-row>
            <v-col cols="5">
              <p class="title text--white ml-8">
                SERVICIOS DE <br />
                SOFTWARE
              </p>
            </v-col>

            <v-col cols="6">
              <v-tabs
                class="d-flex justify-end"
                background-color="rgba(145,25,89,0)"
              >
                <v-tab>quienes somos</v-tab>
                <v-tab>servicios</v-tab>
                <v-tab>testimonios</v-tab>
                <v-tab>equipo</v-tab>
              </v-tabs>
            </v-col>

            <v-col class="d-flex justify-center" cols="1">
              <v-btn icon :to="{ name: 'login' }">
                <v-icon>mdi-account</v-icon>
              </v-btn>
            </v-col>
          </v-row>

          <v-spacer class="pa-8"></v-spacer>

          <v-row>
            <v-col align="center"> </v-col>
          </v-row>

          <v-row class="pt-16">
            <v-col align="center">
              <p class="font-weight-bold display-2 text--white">
                Learn from Industry Experts<br />
              </p>
              <p class="subtitle-1 text--white">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam
                maximus tortor at diam gravida posuere. Curabitur et malesuada
                mi.
              </p>
            </v-col>
          </v-row>
        </v-container>
      </v-img>
    </v-card>


</template>


<script>
export default {
};
</script>