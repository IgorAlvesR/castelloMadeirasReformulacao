<template>
  <v-container class="pa-0" fluid>
    <v-row>
      <v-col cols="12" class="pa-0 ma-0">
        <PrincipalCard />
      </v-col>
      <v-col cols="12" class="d-flex justify-center pt-0 pb-0">
        <QuemSomos />
      </v-col>
    </v-row>
    <Servicos />
    <Contatos />
  </v-container>
</template>

<script>
import PrincipalCard from './PrincipalCard.vue'
import Contatos from './Contatos.vue'
import QuemSomos from './QuemSomos.vue'
import Servicos from './Servicos.vue'

export default {
  components: {
    PrincipalCard,
    Contatos,
    QuemSomos,
    Servicos
  }
}
</script>

<style src="../assets/styles/content.css"></style>
