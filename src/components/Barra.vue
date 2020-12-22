<template>
  <v-app>
    <!-- <div v-if="estado"> -->
    <!-- <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark">
        <a class="navbar-brand" href="# ">
          <img
            src="https://www.flaticon.com/svg/static/icons/svg/1934/1934014.svg"
            width="30 "
            height="30"
            class="d-inline-block align-top"
            alt=" "
            loading="lazy "
          />
          SPRINT 5
        </a>
        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarNav ">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" v-on:click="ingresar" href="# "
                >Sistema <span class="sr-only">(current)</span></a
              >
            </li>
          </ul>
        </div>
      </nav> -->

    <!-- barra superior -->

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
              <!-- <v-btn icon :to="{ name: 'login' }"> -->
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

    <!-- componentes ------------------------------------->
    <router-view />

    <!-- if ------------------------------------->
    <!-- </div>
    <div :to="{ name: 'login' }" v-else > -->
    <!-- <router-view /> -->

    <!-- <v-app id="app">
        <v-navigation-drawer
          v-model="drawer"
          :clipped="$vuetify.breakpoint.lgAndUp" app>
          <v-list dense>
            <template>
              <v-list-item @click="home">
                <v-list-item-action>
                  <v-icon>home</v-icon>
                </v-list-item-action>
                <v-list-item-title> Inicio </v-list-item-title>
              </v-list-item>
            </template>

            <template v-if="logueado">
              <v-list-group>
                <v-list-item slot="activator">
                  <v-list-item-content>
                    <v-list-item-title> Almacén </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item :to="{ name: 'categoria' }">
                  <v-list-item-action>
                    <v-icon>table_chart</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title> Categorías </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item :to="{ name: 'articulo' }">
                  <v-list-item-action>
                    <v-icon>table_chart</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title> Artículos </v-list-item-title>
                  </v-list-item-content>
                </v-list-item> </v-list-group
              >´

              <v-list-group>
                <v-list-item slot="activator">
                  <v-list-item-content>
                    <v-list-item-title> Accesos </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item :to="{ name: 'usuario' }">
                  <v-list-item-action>
                    <v-icon>table_chart</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title> Usuarios </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list-group>
            </template>
          </v-list>
        </v-navigation-drawer>

        <v-app-bar
          :clipped-left="$vuetify.breakpoint.lgAndUp"
          app
          color="silver darken-3"
          dark
        >
          <v-toolbar-title style="width: 300px" class="ml-0 pl-3">
            <v-app-bar-nav-icon
              @click.stop="drawer = !drawer"
            ></v-app-bar-nav-icon>
            <span class="hidden-sm-and-down">Sistema</span>
          </v-toolbar-title>
          <v-spacer></v-spacer>


          <v-btn @click="salir()" icon v-if="logueado">
            <v-icon>logout</v-icon> Salir
          </v-btn>

          <v-btn :to="{ name: 'login' }" icon v-else>
            <v-icon>apps</v-icon> Login
          </v-btn>




        </v-app-bar>


        <v-content>

          <v-container fluid fill-height>
            <v-slide-y-transition mode="out-in">
              <router-view />
            </v-slide-y-transition>
          </v-container>
        </v-content>
        <v-footer height="auto">
          <v-layout justify-center>
            <v-flex text-xs-center>
              <v-card flat tile color="primary" class="white--text">
                <v-card-text class="white--text pt-0">
                  Proyecto final &copy;2020
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-footer>
      </v-app> -->
    <!-- </div> -->
    <!-- </div> -->
  </v-app>
</template>


<script>
export default {
};
</script>