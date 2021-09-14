<template>
  <v-app 
      :elevation="20" class="grey lighten-3">
    <v-app-bar app color="white" flat shrink-on-scroll class="grey lighten-3" >
      <v-container >
        <v-row>
          <v-col cols="12" sm="10" offset-sm="1">
            <Header />
          </v-col>
        </v-row>
      </v-container>
    </v-app-bar>

    <v-main class="grey lighten-3 mb-2">
      <v-container>
        <v-row>
          <v-col cols="12" sm="10" offset-sm="1">
            
              <v-row>
                <v-col>
                  <Nuxt />
                </v-col>
              </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

