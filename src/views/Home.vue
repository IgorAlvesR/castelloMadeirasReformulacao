<template>
  <div class="home">
    <Content />
    <v-btn class="button-float" dark fab bottom right>
      <span class="">
        <a
          class="card-text__link"
          href="https://wa.me/5548998244494?text=Ol%C3%A1%2C+gostaria+de+solicitar+um+or%C3%A7amento%21"
          target="_blank"
        >
          <v-icon color="green">mdi-whatsapp</v-icon>
        </a>
      </span>
    </v-btn>
    <v-btn class="button-float insta" dark fab bottom right>
      <span class="">
        <a
          class="card-text__link"
          href="https://www.instagram.com/castellocasasdemadeira/"
          target="_blank"
        >
          <v-icon color="white">mdi-instagram</v-icon>
        </a>
      </span>
    </v-btn>
  </div>
</template>

<script>
import Content from '../components/Content.vue'

export default {
  name: 'Home',
  components: { Content }
}
</script>
<style scoped>
.card-text__link {
  text-decoration: none;
}
.button-float {
  padding: 10px;
  margin: 0 10px;
  display: block;
  transition: 0.3s;
  position: fixed;
  bottom: 80px;
  right: 10px;
}

.insta {
  bottom: 10px;
}

.button-float .v-icon {
  font-size: 1.7rem;
}

.button-float:hover {
  transform: translateY(-0.35rem);
}
</style>
