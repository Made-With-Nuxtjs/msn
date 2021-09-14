<template>
  <v-if>
    <v-row>
      <v-col>
        <img
          align="center"
          justify="center"
          class="pa-3 ml-9"
          height="200"
          width="273"
          src="https://via.placeholder.com/980"
        />
      </v-col>
    </v-row>
    <v-row align="center" class="ml-9 my-15">
      <v-col>
          <h2 class="mb-5">You May Like</h2>
        <v-card class="mx-auto" flat>
          <v-row>
            <v-col cols="6">
              <v-img
                class="ma-1"
                src="https://picsum.photos/350/165?random"
                height="60"
                width="200"
              ></v-img>
            </v-col>
            <v-col cols="6">
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="truncate-overflow">
                  ‘It’s still resonating’ 9/11 families on the last
                </h5>
              </nuxt-link>
              <nuxt-link to="#" class="text-decoration-none"
                ><h6 class="py-2 text--secondary">
                  Real Estate com.
                </h6></nuxt-link
              >
            </v-col>
          </v-row>
        </v-card>
        <v-card class="mx-auto" flat>
          <v-row>
            <v-col cols="6">
              <v-img
                class="ma-1"
                src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                height="60"
                width="200"
              ></v-img>
            </v-col>
            <v-col cols="6">
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="truncate-overflow">
                  ‘It’s still resonating’ 9/11 families on the last
                </h5>
              </nuxt-link>
              <nuxt-link to="#" class="text-decoration-none"
                ><h6 class="py-2 text--secondary">
                  Real Estate com.
                </h6></nuxt-link
              >
            </v-col>
          </v-row>
        </v-card>
        <v-card class="mx-auto" flat>
          <v-row>
            <v-col cols="6">
              <v-img
                class="ma-1"
                src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                height="60"
                width="200"
              ></v-img>
            </v-col>
            <v-col cols="6">
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="truncate-overflow">
                  ‘It’s still resonating’ 9/11 families on the last
                </h5>
              </nuxt-link>
              <nuxt-link to="#" class="text-decoration-none"
                ><h6 class="py-2 text--secondary">
                  Real Estate com.
                </h6></nuxt-link
              >
            </v-col>
          </v-row>
        </v-card>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <img
          align="center"
          justify="center"
          class="pa-3 ml-9"
          height="200"
          width="273"
          src="https://via.placeholder.com/980"
        />
      </v-col>
    </v-row>
  </v-if>
</template>


<script>
export default {
  data() {
    return {
      page: 1,
    }
  },
}
</script>


<style scoped>
.truncate-overflow {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 2;
  white-space: normal;
}
</style>
