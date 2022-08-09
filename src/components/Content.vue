<template>
  <v-container class="pa-0" fluid>
    <v-row>
      <v-col cols="12">
        <PrincipalCard />
      </v-col>
      <v-col cols="6">
        <v-card> </v-card>
      </v-col>
      <v-col cols="6"> </v-col>
    </v-row>
  </v-container>
</template>

<script>
import PrincipalCard from './PrincipalCard.vue'

export default {
  components: {
    PrincipalCard
  }
}
</script>

<style src="../assets/styles/content.css"></style>
