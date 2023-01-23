<template>
  <v-row id="contato">
    <v-col cols="12" class="pt-0 pb-0 pl-0 pr-0">
      <v-card dark tile>
        <v-card-title id="contato" class="red-text justify-center"
          >Contato</v-card-title
        >
      </v-card>
    </v-col>
    <v-col cols="12" class="pa-0">
      <v-card
        elevation="2"
        tile
        dark
        class="text-center pl-8 pr-8 d-flex flex-column align-center"
      >
        <v-card-text class="max-width-500">
          <span class="card-text__numbers">
            <a
              class="card-text__link"
              href="https://wa.me/5548998244494?text=Ol%C3%A1%2C+gostaria+de+solicitar+um+or%C3%A7amento%21"
              target="_blank"
            >
              <v-icon color="red" class="card-text__wpp">mdi-whatsapp</v-icon>
            </a>
            (48) 99824-4494
          </span>
        </v-card-text>
        <v-card-text class="max-width-500">
          <span class="card-text__numbers">
            <a
              class="card-text__link"
              href="https://wa.me/5548998572530?text=Ol%C3%A1%2C+gostaria+de+solicitar+um+or%C3%A7amento%21"
              target="_blank"
            >
              <v-icon color="red" class="card-text__wpp">mdi-whatsapp</v-icon>
            </a>
            (48) 99857-2530
          </span>
        </v-card-text>
        <v-card-text class="max-width-500">
          <span class="card-text__numbers">
            <v-icon color="red">mdi-phone</v-icon>
            (48) 3632-8743
          </span>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>
<style scoped src="../assets/styles/contatos.css"></style>
