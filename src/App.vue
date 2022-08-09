<template>
  <v-app>
    <Header />
    <v-main class="pa-0">
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>
<style scoped lang="css">
@import './assets/styles/app.css';
</style>
