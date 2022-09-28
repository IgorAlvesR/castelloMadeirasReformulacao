<template>
  <v-container class="mb-6">
    <v-app-bar dark app>
      <v-app-bar-nav-icon
        class="d-flex d-md-none"
        @click.stop="drawer = !drawer"
      />
      <v-img class="mr-2" max-width="30" src="../assets/logo.png" />
      <v-toolbar-title style="width: 50%">
        <a class="link-home" href="#inicio">Castello Madeiras</a>
      </v-toolbar-title>
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

<style scoped>
.link-home {
  text-decoration: none;
  color: #fff;
}
</style>
