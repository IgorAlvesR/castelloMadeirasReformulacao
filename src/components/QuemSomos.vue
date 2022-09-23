<template>
  <v-card
    id="quem-somos"
    width="100vw"
    class="pa-0"
    elevation="2"
    outlined
    tile
  >
    <v-row class="mt-4 mb-4 d-flex justify-center">
      <v-col sm="4" cols="12" class="d-flex align-center">
        <v-container class="d-flex justify-center">
          <v-img
            class="quem-somos-img"
            max-height="150"
            max-width="200"
            src="@/assets/quemsomos.png"
          ></v-img>
        </v-container>
      </v-col>
      <v-col sm="6" cols="12">
        <v-container class="pt-16 pb-16">
          <v-card-title class="red-text title"> Quem somos </v-card-title>
          <v-card-text class="subtitle-1">
            A Castello Madeiras é uma empresa situada em Tubarão-SC que atua no
            ramo de construção de casa pré-fabricada de madeira, elaboramos seu
            projeto personalizado, com uma equipe qualificada para atender a
            necessidade da sua família com o novo lar. Casas modernas, na
            cidade, no campo e na praia. Agradáveis, arejadas no verão e
            aconchegantes no inverno.
          </v-card-text>
        </v-container>
      </v-col>
    </v-row>
  </v-card>
</template>

<style scoped>
@keyframes scroll {
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-0.8rem);
  }
  100% {
    transform: translateY(0);
  }
}

.quem-somos-img {
  animation: scroll 2s infinite;
}
</style>
