<template>
  <v-card id="inicio">
    <v-img
      height="100vh"
      class="align-center"
      src="../assets/images/principal.jpg"
    >
      <v-card-title
        class="title-carousel justify-center"
        v-text="`Se você pode sonhar, você pode realizar.`"
      />
      <v-card-actions class="actions-card justify-center mt-16">
        <v-btn
          class="px-4"
          color="white"
          outlined
          x-large
          target="blank"
          href="catalago.pdf"
        >
          Clique para ver o modelo de casas
        </v-btn>
      </v-card-actions>
    </v-img>
  </v-card>
</template>
<style scoped src="../assets/styles/principalCard.css"></style>
