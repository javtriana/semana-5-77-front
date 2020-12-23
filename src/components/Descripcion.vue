<template>
  <v-container>
    <v-row class="d-flex justify-space-between">
      <v-col max-height="150">
        <v-hover v-slot="{ hover }" light>
          <v-card
            :elevation="hover ? 4 : 2"
            class="mx-auto"
            height="250"
            max-width="350"
          >
            <v-container>
              <v-row class="d-flex justify-center mt-2">
                <v-icon size="60px" color=rgba(8,126,223,1)>mdi-lightbulb-on</v-icon>
              </v-row>

              <v-row class="d-flex justify-center mt-5">
                <p class="font-weight-bold headline text--white">
                  Actionable Training
                </p>
              </v-row>

              <v-row class="d-flex justify-center mt-3">
                <p class=" subtitle-1 text--white">
                  Lorem ipsum dolor sit amet,<br/>
                  Lorem ipsum dolor sit amet,
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
            height="250"
            max-width="350"
          >
            <v-container>
              <v-row class="d-flex justify-center mt-2">
                <v-icon size="60px" color=rgba(8,126,223,1)>mdi-lightbulb-on</v-icon>
              </v-row>

              <v-row class="d-flex justify-center mt-5">
                <p class="font-weight-bold headline text--white">
                  Actionable Training
                </p>
              </v-row>

              <v-row class="d-flex justify-center mt-3">
                <p class=" subtitle-1 text--white">
                  Lorem ipsum dolor sit amet,<br/>
                  Lorem ipsum dolor sit amet,
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
            height="250"
            max-width="350"
          >
            <v-container>
              <v-row class="d-flex justify-center mt-2">
                <v-icon size="60px" color=rgba(8,126,223,1)>mdi-lightbulb-on</v-icon>
              </v-row>

              <v-row class="d-flex justify-center mt-5">
                <p class="font-weight-bold headline text--white">
                  Actionable Training
                </p>
              </v-row>

              <v-row class="d-flex justify-center mt-3">
                <p class=" subtitle-1 text--white">
                  Lorem ipsum dolor sit amet,<br/>
                  Lorem ipsum dolor sit amet,
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
  },
};
</script>