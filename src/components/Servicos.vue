<template>
  <v-container class="pt-16 pb-16" id="servicos">
    <v-timeline dense>
      <v-timeline-item color="red lighten-1">
        <template v-slot:opposite>
          <v-icon>mdi-toilet</v-icon>
          <span>Hidráulica</span>
        </template>
        <v-card class="elevation-2" dark>
          <v-card-title class="text-h5">
            <v-icon>mdi-toilet</v-icon>
            Hidráulica
          </v-card-title>
          <v-card-text>
            A instalação hidráulica representa 3% do custo total da obra, e nós
            entregamos a casa com toda parte hidráulica pronta para uso.
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item color="red lighten-1">
        <template v-slot:opposite>
          <v-icon>mdi-lightning-bolt-outline</v-icon>
          <span>Elétrica</span>
        </template>
        <v-card class="elevation-2" dark>
          <v-card-title class="text-h5">
            <v-icon>mdi-lightning-bolt-outline</v-icon>
            Elétrica
          </v-card-title>
          <v-card-text>
            Sem dor de cabeça com eletricista, a Castello entrega a parte
            elétrica pronta para uso.
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item color="red lighten-1">
        <template v-slot:opposite>
          <v-icon>mdi-floor-plan</v-icon>
          <span>Pisos</span>
        </template>
        <v-card class="elevation-2" dark>
          <v-card-title class="text-h5">
            <v-icon>mdi-floor-plan</v-icon>
            Pisos
          </v-card-title>
          <v-card-text>
            Junto ao pacote acompanha os pisos de sua casa.
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item color="red lighten-1">
        <template v-slot:opposite>
          <v-icon>mdi-wall</v-icon>
          <span>Parede Duplada</span>
        </template>
        <v-card class="elevation-2" dark>
          <v-card-title class="text-h5">
            <v-icon>mdi-wall</v-icon>
            Parede Duplada
          </v-card-title>
          <v-card-text>
            Temos a opção de parede duplada, para maior conforto e comodidade
          </v-card-text>
        </v-card>
      </v-timeline-item>
    </v-timeline>
  </v-container>
</template>
