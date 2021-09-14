<template>
  <v-row>
    <v-col cols="12" sm="6" md="6">
      <v-row>
        <v-carousel
          cycle
          height="400"
          hide-delimiter-background
          show-arrows-on-hover
          class="ml-5 mr-2 my-5"
        >
        <nuxt-link to="treanding" class="text-decoration-none">
          <v-carousel-item v-for="(slide, i) in slides" :key="i">
            <v-sheet :color="colors[i]" height="100%">
              <v-row class="fill-height" align="center" justify="center">
                <div class="text-h2">{{ slide }} Slide</div>
              </v-row>
            </v-sheet>
          </v-carousel-item>
          </nuxt-link>
        </v-carousel>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-row>
            <v-col cols="12" sm="6">
              <v-card
                class="mx-auto mb-3"
                max-width="350"
                max-height="100"
                outlined
              >
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last 20
                      years
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
              <v-card
                class="mx-auto mb-3"
                max-width="350"
                outlined
                max-height="100"
              >
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5>
                      Just shoot me': Afghan star recalls surreal Kabul escape
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> AFP
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
            </v-col>
            <v-col cols="12" sm="6">
              <v-card
                class="mx-auto mb-3"
                max-width="344"
                outlined
                max-height="100"
              >
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.pixabay.com/photo/2020/06/24/19/12/cabbage-5337431_1280.jpg"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5>Find deals on hotels, homes, and much more.</h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> Espresso
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
              <v-card
                class="mx-auto mb-3"
                max-width="344"
                outlined
                max-height="100"
              >
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/plane.jpg"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5>Tricky questions almost everybody gets wrong!</h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> Booking.com
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-col>
    <!-- ---Right side -->
    <v-col cols="12" sm="6" md="6">
      <v-row>
        <v-col cols="12" sm="12">
          <v-row>
            <v-col cols="12" sm="6">
              <v-card height="270px" class="mb-4 mt-2">
                <v-img
                  class="ma-1"
                  src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"
                  height="266"
                ></v-img>
              </v-card>
              <v-card class="mx-auto" max-width="344" outlined>
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"
                      height="95"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last 20
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
            </v-col>
            <v-col cols="12" sm="6">
              <v-card height="270px" class="mb-4 mt-2">
                <v-img
                  class="ma-1"
                  src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"
                  height="266px"
                ></v-img>
              </v-card>
              <v-card class="mx-auto" max-width="344" outlined>
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"
                      height="95"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last 20
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
            </v-col>
          </v-row>
        </v-col>
      </v-row>

      <v-row>
        <v-col cols="12">
          <v-row class="pt-4">
            <v-col cols="12" sm="6">
              <v-card class="mx-auto mb-3" max-width="344" outlined>
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last 202
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
              <v-card class="mx-auto mb-3" max-width="344" outlined>
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://picsum.photos/510/300?random"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last 20

                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
            </v-col>
            <v-col cols="12" sm="6">
              <v-card class="mx-auto mb-3" max-width="344" outlined>
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://picsum.photos/350/165?random"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
              </v-card>
              <v-card class="mx-auto mb-3" max-width="344" outlined>
                <v-row>
                  <v-col cols="5">
                    <v-img
                      class="ma-1"
                      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                      height="90"
                    ></v-img>
                  </v-col>
                  <v-col cols="7">
                    <h5 height="50">
                      ‘It’s still resonating’: 9/11 families on the last 20
                    
                    </h5>
                    <nuxt-link to="#" class="text-decoration-none">
                      <h6 class="pt-8">
                        <v-icon>mdi-fleur-de-lis</v-icon> The Independent
                      </h6></nuxt-link
                    >
                  </v-col>
                </v-row>
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
      colors: [
        'indigo',
        'warning',
        'pink darken-2',
        'red lighten-1',
        'deep-purple accent-4',
      ],
      slides: ['Nirob', 'Second', 'Third', 'Fourth', 'Fifth'],
    }
  },
}
</script>