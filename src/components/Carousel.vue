  
  <template>
  <!-- <v-container fluid> -->
  <v-layout mt-2 mb-4 fluid>
    <v-flex>
      <v-carousel height="650px">
        <v-carousel-item
          v-for="(item, i) in items"
          :key="i"
          :src="item.src"
          gradient="to right, rgba(8,126,223,.1), rgba(1,66,182,.5)"
          reverse-transition="fade-transition"
          transition="fade-transition"
        >
          <v-spacer class="pa-16"></v-spacer>

          <v-container mt-14>
            <v-row class="d-flex justify-center mt-5">
              <v-col cols="6" align="center">
                <p class="font-weight-bold display-2 text--white">
                  Actionable Training
                </p>
              </v-col>
            </v-row>

            <v-row class="d-flex justify-center mt-3">
              <v-col cols="6" align="center">
                <p class="headline text--white">
                  Lorem ipsum dolor sit amet, consectetur . <br />
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                </p>
              </v-col>
            </v-row>
          </v-container>
        </v-carousel-item>
      </v-carousel>
    </v-flex>
  </v-layout>
  <!-- </v-container> -->
</template>



<script>
export default {
  data() {
    return {
      items: [
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/bird.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg",
        },
      ],
    };
  },
};
</script>