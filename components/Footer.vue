<template>
  <v-row>
    <v-col cols="6" sm="3">
      <v-icon>mdi-checkerboard</v-icon> <span>ICT Layer</span><br />
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-col>
    <v-col cols="6" sm="3">
      <v-row>
        <v-col cols="6">
          <v-img
            max-height="28"
            max-width="132"
            class="py-5 mb-3 ml-2"
            src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?"
            
          ></v-img>
          <v-img
           max-height="30"
            max-width="150"
            class="py-5"
            src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png"
          ></v-img>
        </v-col>
        <v-col cols="6">
          <v-btn
            color="primary"
            small
            class="ma-2 white--text"
          >
            <v-icon right dark> mdi-thumb-up </v-icon> <span class="pl-2">Likes</span><span class="pl-2">17K</span>
          </v-btn>
         <v-btn
            color="blue"
            small
            class="ma-2 white--text"
          >
            <v-icon right dark> mdi-twitter </v-icon> <span class="pl-2">Follow</span>
          </v-btn>
        </v-col>
      </v-row>
    </v-col>
    <v-col cols="6" sm="3">
      <v-row>
        <v-col cols="6" >
        <h6 class="pl-3">Privacy & Cookies</h6>
        <h6 class="pl-3">Manage Preference</h6>
        <h6 class="pl-3">Terms of use</h6>
        </v-col>
        <v-col cols="6">
           <h6 class="pl-3">About our ads</h6>
        <h6 class="pl-3">Feedback</h6>
        <h6 class="pl-3">Help</h6>
        </v-col>
      </v-row>
    </v-col>
    <v-col cols="6" sm="3">
      <h6 class="pl-3">MSN Worldwide</h6>
    </v-col>
  </v-row>
</template>