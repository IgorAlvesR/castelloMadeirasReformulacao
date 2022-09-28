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
        require('../assets/gridImages/img01.jpeg'),
        require('../assets/gridImages/img02.jpeg'),
        require('../assets/gridImages/img03.jpeg'),
        require('../assets/gridImages/img04.jpeg'),
        require('../assets/gridImages/img06.jpeg'),
        require('../assets/gridImages/img07.jpeg'),
        require('../assets/gridImages/img08.jpeg'),
        require('../assets/gridImages/img09.jpeg'),
        require('../assets/gridImages/img10.jpeg'),
        require('../assets/gridImages/img11.jpeg'),
        require('../assets/gridImages/img12.jpeg'),
        require('../assets/gridImages/img13.jpeg'),
        require('../assets/gridImages/img14.jpeg'),
        require('../assets/gridImages/img15.jpeg'),
        require('../assets/gridImages/img16.jpeg')
      ]
    }
  }
}
</script>

<style lang="scss" scoped></style>
