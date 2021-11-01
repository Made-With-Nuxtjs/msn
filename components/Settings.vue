<template>
  <div class="text-left">
    <v-menu
      :close-on-content-click="false"
      :nudge-width="250"
      offset-x
      transition="scroll-y"
    >
      <!-- //Template for icom on header bar// -->
      <template #activator="{ on, attrs }">
        <v-btn icon class="d-none d-sm-flex" v-bind="attrs" v-on="on">
          <v-icon>mdi-cog-outline</v-icon>
        </v-btn>
      </template>
      <v-card fill-height>
        <v-card-subtitle>CHANGE LANGUAGE & CONTENT:</v-card-subtitle>
        <v-overflow-btn
          flat
          dense
          tile
          :items="dropdown_edit"
          label="United State"
          counter
          item-value="text"
        ></v-overflow-btn>
      </v-card>
    </v-menu>
  </div>
</template>

<script>
export default {
  data: () => ({
    dropdown_edit: [
      { text: 'Switzerland' },
      { text: 'Taiwan' },
      { text: 'Turkey' },
      { text: 'United Arab Emirates' },
      { text: 'United Kingdom' },
      { text: 'United States' },
      { text: 'Zimbabwe' },
      { text: 'Malaysia' },
      { text: 'Italy' },
      { text: 'Ireland' },
      { text: 'United Kingdom' },
      { text: 'United Kingdom' },
      { text: 'United Kingdom' },
      { text: 'United Kingdom' },
      { text: 'United Kingdom' },
      { text: 'United Kingdom' },
      { text: 'United Kingdom' },
    ],
  }),
}
</script>
