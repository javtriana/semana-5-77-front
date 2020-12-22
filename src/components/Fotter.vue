<template >
  <v-footer
    class="pt-10"
    height="250"
    dark
    padless
    color="rgba(1,66,182,1)"
    gradient="to right, rgba(8,126,223,1), rgba(1,66,182,1)"
  >
    <v-card
      class="flex"
      flat
      tile
      color="rgba(1,66,182,1)"
      gradient="to right, rgba(8,126,223,1), rgba(1,66,182,1)"
    >
      <v-card-title>
        <strong class="subheading"
          >Get connected with us on social networks!</strong
        >

        <v-spacer></v-spacer>

        <v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-title>

      <v-card-text class="py-2 white--text text-center">
        {{ new Date().getFullYear() }} —
        <strong>Software Development Team</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>


<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>