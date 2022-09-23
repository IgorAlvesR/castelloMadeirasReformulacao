<template>
  <v-list nav dense>
    <v-list-item-group :value="group" @change="$emit('update:group', $event)">
      <v-list-item href="#quem-somos">
        <v-list-item-title>Quem Somos</v-list-item-title>
      </v-list-item>

      <v-list-item href="#sonhos-realizados">
        <v-list-item-title>Sonhos Realizados</v-list-item-title>
      </v-list-item>

      <v-list-item href="#servicos">
        <v-list-item-title>Serviços</v-list-item-title>
      </v-list-item>

      <v-list-item href="#contato">
        <v-list-item-title>Contato</v-list-item-title>
      </v-list-item>
    </v-list-item-group>
  </v-list>
</template>

<script>
export default {
  data: () => ({
    group: null
  })
}
</script>
