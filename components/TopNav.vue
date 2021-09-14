<template>           
  <v-card flat class="mt-n4">
    <v-tabs
      color="black accent-4"
    >
      <v-tabs-slider color="blue" />
      <v-tab>
        <nuxt-link to="asia" class="text-decoration-none">
         <span class="text--primary caption"> Headlines</span>
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="pakistan" class="text-decoration-none">
          <span class="text--primary caption"> Pakistan</span>
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="bangladesh" class="text-decoration-none">
           <span class="text--primary caption"> Bangladesh</span>
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="sports" class="text-decoration-none">
          <span class="text--primary caption"> Sports</span>
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="videos" class="text-decoration-none">
          <span class="text--primary caption"> Videos</span>
        </nuxt-link>
      </v-tab>
    </v-tabs>
  </v-card>    
</template>
