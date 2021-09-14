<template>
  <v-card flat class="py-12">
    <v-card-text>
      <v-row align="center" justify="center" class="float-right">
        <v-btn-toggle v-model="toggle_exclusive" rounded shrink-on-scroll>
          <div>
            <div class="d-block pa-1">
              <nuxt-link to="#" class="text-decoration-none">
                <v-icon color="teal darken-2" size="35"> mdi-linkedin </v-icon>
              </nuxt-link>
            </div>
            <div class="d-block pa-1">
              <nuxt-link to="#" class="text-decoration-none">
                <v-icon color="blue darken-2" size="35"> mdi-facebook</v-icon>
              </nuxt-link>
            </div>
            <div class="d-block pa-1">
              <nuxt-link to="#" class="text-decoration-none">
                <v-icon color="blue darken-2" size="35"> mdi-twitter </v-icon>
              </nuxt-link>
            </div>
            <div class="d-block pa-1">
              <nuxt-link to="#" class="text-decoration-none">
                <v-icon color="green darken-2" size="35"> mdi-whatsapp </v-icon>
              </nuxt-link>
            </div>
            <div class="d-block pa-1">
              <nuxt-link to="#" class="text-decoration-none">
                <v-icon color="darken-2" size="35"> mdi-email </v-icon>
              </nuxt-link>
            </div>
          </div>
        </v-btn-toggle>
      </v-row>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      toggle_exclusive: undefined,
    }
  },
}
</script>