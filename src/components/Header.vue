<template>
  <v-container fluid class="mb-6">
    <v-app-bar dark dense app>
      <v-app-bar-nav-icon
        class="d-flex d-md-none"
        @click.stop="drawer = !drawer"
      />
      <v-img class="mr-2" max-width="30" src="../assets/logo.png" />
      <v-app-bar-title style="width: 50%">Castello Madeiras</v-app-bar-title>
      <v-spacer></v-spacer>
      <Navigation v-if="!($vuetify.breakpoint.xs || $vuetify.breakpoint.sm)" />
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" app temporary>
      <ListMenuMobile @update:group="drawer = false" />
    </v-navigation-drawer>
  </v-container>
</template>
<script>
import ListMenuMobile from './ListMenuMobile.vue'
import Navigation from './Navigation.vue'

export default {
  components: {
    ListMenuMobile,
    Navigation
  },
  data: () => ({
    drawer: false
  })
}
</script>
