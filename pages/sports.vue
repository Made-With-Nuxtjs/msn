<template>
  <if>
    <v-row>
      <v-col cols="12">
        <TopNavSports />
       <v-card class="mb-4 mt-2">
            <AdsHeader />
          </v-card>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="6" md="6">
        <v-carousel
          cycle
          height="400"
          hide-delimiter-background
          show-arrows-on-hover
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
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-row>
          <v-col cols="12" sm="6" md="6">
            <v-hover v-slot="{ hover }" open-delay="20">
              <v-card
                class="mx-auto mb-3"
                height="390"
                outlined
                :elevation="hover ? 20 : 2"
                :class="{ 'on-hover': hover }"
              >
                <img
                  src="https://picsum.photos/500/300?image=550"
                  width="346"
                />
                <nuxt-link to="#" class="text-decoration-none">
                  <h6 class="pa-2">
                    <v-icon size="17">mdi-google-chrome</v-icon>
                    Reuters
                  </h6>
                </nuxt-link>
                <v-card-text>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h2 class="text--primary">
                      Taliban takeover of Afghanistan is an ‘earthquake’ for
                      Middle East
                    </h2>
                  </nuxt-link>
                </v-card-text>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="12" sm="6" md="6">
            <v-hover v-slot="{ hover }" open-delay="20">
              <v-card
                class="mx-auto mb-3"
                height="390"
                outlined
                :elevation="hover ? 16 : 2"
                :class="{ 'on-hover': hover }"
              >
                <img
                  src="https://picsum.photos/500/300?image=600"
                  width="346"
                />
                <nuxt-link to="#" class="text-decoration-none">
                  <h6 class="pa-2">
                    <v-icon size="17">mdi-google-chrome</v-icon>
                    Reuters
                  </h6>
                </nuxt-link>
                <v-card-text>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h2 class="text--primary">
                      Israeli spyware firm targeted Apple devices via iMessage,
                      researchers say
                    </h2>
                  </nuxt-link>
                </v-card-text>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=500" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=501" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=502" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=503" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=504" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=505" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=506" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=507" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=508" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=509" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=510" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="3" md="3">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            class="mx-auto mb-3"
            max-height="1000"
            outlined
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
          >
            <img src="https://picsum.photos/500/300?image=511" width="345" />
            <nuxt-link to="#" class="text-decoration-none">
              <h6 class="pa-2">
                <v-icon size="17">mdi-google-chrome</v-icon>
                Reuters
              </h6>
            </nuxt-link>
            <v-card-text>
              <nuxt-link to="#" class="text-decoration-none">
                <h2 class="text--primary">
                  Vietnam's biggest city to keep virus curbs, flight resumption
                  sought
                </h2>
              </nuxt-link>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos
                dolore ducimus fuga maiores totam quis ut harum tenetur
                quisquam! Officia sint sit neque, corporis aut vel praesentium
                expedita ullam deleniti!
              </p>
            </v-card-text>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
  </if>
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