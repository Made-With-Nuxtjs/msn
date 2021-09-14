<template>
  <v-row>
    <v-col cols="12" sm="12">
      <v-row>
        <v-col cols="12" >
          <v-row>
            <v-col cols="12" sm="3">
              <v-card class="mb-4 mt-2">
                <v-img
                  class="ma-1"
                  src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"
                  height="266"
                ></v-img>
                <h4 class="pl-3 text--secondary">সৌরভ গঙ্গোপাধ্যায়</h4>
                <v-card-actions>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h6 class="pt-8">
                      <v-icon size="17">mdi-google-chrome</v-icon> The Independent
                    </h6></nuxt-link
                  >
                </v-card-actions>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mb-4 mt-2">
                <v-img
                  class="ma-1"
                  src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"
                  height="266"
                ></v-img>
                <h4 class="pl-3 text--secondary">ছবিতে দ্রাবিড় কাহিনি</h4>
                <v-card-actions>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h6 class="pt-8">
                      <v-icon size="17">mdi-google-chrome</v-icon> The Independent
                    </h6></nuxt-link
                  >
                </v-card-actions>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mb-4 mt-2">
                <v-img
                  class="ma-1"
                  src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"
                  height="266"
                ></v-img>
                <h4 class="pl-3 text--secondary">বিশ্বজয়ী হ্যারিকেন</h4>
                <v-card-actions>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h6 class="pt-8">
                      <v-icon size="17">mdi-google-chrome</v-icon> The Independent
                    </h6></nuxt-link
                  >
                </v-card-actions>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mb-4 mt-2">
                <v-img
                  class="ma-1"
                  src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"
                  height="266"
                ></v-img>
                <h4 class="pl-3 text--secondary">কপিল কথা</h4>
                <v-card-actions>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h6 class="pt-8">
                      <v-icon size="17">mdi-google-chrome</v-icon> The Independent
                    </h6></nuxt-link
                  >
                </v-card-actions>
              </v-card>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template>




<script>
export default {
  data() {
    return {
      items: [
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg',
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
        },
      ],
    }
  },
}
</script>