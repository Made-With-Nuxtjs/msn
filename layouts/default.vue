<template>
  <v-app :elevation="20">
    <v-app-bar app color="white" flat shrink-on-scroll class="grey lighten-3">
      <v-row no-gutters class="mt-10">
        <v-col sm="12" md="10" offset-md="1">
          <v-card class="d-flex justify-space-around text-center py-4 mx-auto" flat tile>
            <v-card class="my-auto" tile flat>
              <NuxtLink to="/" class="text-decoration-none"
                ><v-icon>mdi-butterfly-outline</v-icon> msn</NuxtLink
              >
            </v-card>
            <v-card class="my-auto" flat tile width="50%">
              <v-text-field
              class="mb-n6"
                tile
                solo-inverted
                placeholder="Search"
                outlined
                dense
                append-icon="mdi-magnify"
              >
              </v-text-field>
            </v-card>
            <v-card flat class="my-auto">
              <v-col
                cols="12"
                sm="3"
                class="d-flex justify-space-between text-center"
              >
                <NuxtLink to="#" class="text-decoration-none">
                  <v-btn icon class="text-capitalize"> Sign in </v-btn>
                </NuxtLink>
                <Settings class="mr-n6"/>
              </v-col>
            </v-card>
          </v-card>
        </v-col>
      </v-row>
    </v-app-bar>

    <v-main class="grey lighten-3 mx-4">
    
          <Nuxt />
        
    </v-main>
  </v-app>
</template>
