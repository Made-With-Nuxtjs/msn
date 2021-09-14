<template>
  <v-if>
    <v-card
      class="d-flex justify-space-around text-center my-2"
      :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
      flat
      tile
    >
      <v-card class="ma-2" tile flat>
        <CategoryChips />
        <v-divider inset class="mr-15"></v-divider>
      </v-card>
    </v-card>
    <v-card class="my-4">
      <AdsHeader />
    </v-card>
    <v-card
      class="d-flex justify-center"
      :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
      flat
      tile
    >
      <v-card tile flat>
        <SpecialChips />
      </v-card>
    </v-card>

    <v-card
      class="d-flex justify-center"
      :color="$vuetify.theme.dark ? 'white ' : 'white lighten-4'"
      flat
      tile
    >
      <v-card tile flat>
        <HomePortion />

        <v-divider class="ma-2 black"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="black--text"
                >Bangla<v-icon>mdi-chevron-right</v-icon></span
              ></nuxt-link
            >
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="black--text"
                >Edit<v-icon>mdi-chevron-down</v-icon></span
              ></nuxt-link
            >
          </v-card>
        </v-card>

        <BanglaPortion />
        <v-divider class="ma-2 blue"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span>Cricket<v-icon>mdi-chevron-right</v-icon></span></nuxt-link
            >
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span>Edit<v-icon>mdi-chevron-down</v-icon></span></nuxt-link
            >
          </v-card>
        </v-card>
        <CricketPortion />
        <v-divider class="ma-2 purple"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="purple--text"
                >Life<v-icon>mdi-chevron-right</v-icon></span
              ></nuxt-link
            >
          </v-card>

          <v-card class="pa-1" flat>
            <LifeEventChips />
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="purple--text"
                >Edit<v-icon>mdi-chevron-down</v-icon></span
              ></nuxt-link
            >
          </v-card>
        </v-card>
        <LifePortion />

        <v-divider class="ma-2 green"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="green--text"
                >Asia<v-icon>mdi-chevron-right</v-icon></span
              ></nuxt-link
            >
          </v-card>

          <v-card class="pa-1" flat>
            <AsiaEventChips />
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="green--text"
                >Edit<v-icon>mdi-chevron-down</v-icon></span
              ></nuxt-link
            >
          </v-card>
        </v-card>
        <AsiaPortion />
        <v-divider class="ma-2 orange"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="orange--text"
                >Esports<v-icon>mdi-chevron-right</v-icon></span
              ></nuxt-link
            >
          </v-card>

          <v-card class="pa-1" flat>
            <EsportsItemChips />
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="orange--text"
                >Edit<v-icon>mdi-chevron-down</v-icon></span
              ></nuxt-link
            >
          </v-card>
        </v-card>
        <EsportsPortion />
        <v-divider class="ma-2 red"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="red--text"
                >From Our Partners<v-icon>mdi-chevron-right</v-icon></span
              ></nuxt-link
            >
          </v-card>

          <v-card class="pa-1" flat>
            <PartnerNameChips />
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="red--text"
                >Edit<v-icon>mdi-chevron-down</v-icon></span
              ></nuxt-link
            >
          </v-card>
        </v-card>
        <PartnerPortion />
        <v-divider class="ma-2 blue"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span>Business<v-icon>mdi-chevron-right</v-icon></span></nuxt-link
            >
          </v-card>

          <v-card class="pa-1" flat>
            <PartnerNameChips />
          </v-card>
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span>Edit<v-icon>mdi-chevron-down</v-icon></span></nuxt-link
            >
          </v-card>
        </v-card>
        <BusinessPortion />
        <v-divider class="ma-2 purple"></v-divider>
        <v-card
          class="d-flex justify-space-between"
          :color="$vuetify.theme.dark ? 'white darken-3' : 'white lighten-4'"
          flat
          tile
        >
          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="purple--text"
                >Videos<v-icon>mdi-chevron-right</v-icon></span
              ></nuxt-link
            >
          </v-card>

          <v-card class="pa-2" flat>
            <nuxt-link to="#" class="text-decoration-none">
              <span class="purple--text"
                >Edit<v-icon>mdi-chevron-down</v-icon></span
              ></nuxt-link
            >
          </v-card>
        </v-card>
        <VideosPortion />
        <Footer />
      </v-card>
    </v-card>
  </v-if>
</template>
