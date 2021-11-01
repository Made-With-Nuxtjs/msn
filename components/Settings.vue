<template>
  <div class="text-center">
    <v-menu transition="scale-transition" origin="center center">
      <template #activator="{ on, attrs }">
        <v-icon class="mt-2 pl-3" v-bind="attrs" v-on="on"
          >mdi-cog-outline</v-icon
        >
      </template>
      <v-card>
        <v-row align="center">
          <v-col class="d-flex" cols="12" sm="6">
            <v-select
              :items="items"
              label="Outlined style"
              dense
              outlined
            ></v-select>
          </v-col>
        </v-row>
      </v-card>
    </v-menu>
  </div>
</template>











<script>
  export default {
    data: () => ({
      items: ['Foo', 'Bar', 'Fizz', 'Buzz'],
    }),
  }
</script>
