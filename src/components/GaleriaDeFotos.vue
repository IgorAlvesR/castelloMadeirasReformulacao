<template>
  <v-card dark>
    <v-container class="pt-16 pb-16" id="sonhos-realizados">
      <v-row>
        <v-col
          v-for="(image, index) in images"
          :key="index"
          class="d-flex child-flex"
          cols="6"
          sm="4"
        >
          <v-img
            :src="image"
            :lazy-src="image"
            aspect-ratio="1"
            class="grey lighten-2"
          >
            <template v-slot:placeholder>
              <v-row class="fill-height ma-0" align="center" justify="center">
                <v-progress-circular
                  indeterminate
                  color="grey lighten-5"
                ></v-progress-circular>
              </v-row>
            </template>
          </v-img>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      images: [
        require('../assets/img02.jpeg'),
        require('../assets/img03.jpeg'),
        require('../assets/img04.jpeg'),
        require('../assets/img05.jpeg'),
        require('../assets/img06.jpeg'),
        require('../assets/img07.jpeg')
      ]
    }
  }
}
</script>

<style lang="scss" scoped></style>
