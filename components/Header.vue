<template>
    <v-card
      class="d-flex justify-space-around text-center pb-2"
      flat
      tile
    >
      <v-card class="pt-10" tile flat>
       <nuxt-link to="/" class="text-decoration-none"><v-icon>mdi-butterfly-outline</v-icon> msn</nuxt-link> 
      </v-card>
      <v-card class="pt-10" flat tile width="50%">
        <v-text-field
          placeholder="Placeholder"
          outlined
          dense
          append-icon="mdi-magnify"
        >
        </v-text-field>
      </v-card>
      <v-card flat class="pt-3">
        <v-col
          cols="12"
          sm="3"
          class="d-flex justify-space-between text-center"
        >
          <nuxt-link to="#" class="text-decoration-none ">
            <v-btn icon class="text-capitalize"> Sign in </v-btn>
          </nuxt-link>
          <Settings/>
        </v-col>
      </v-card>
    </v-card>
</template>

