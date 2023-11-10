<template>
  <HeaderApp />
  <div class="d-flex flex-wrap height-black ">
    <Card v-for="contact in lista" :thumb="contact.thumb" :series="contact.series" :type="contact.type" />
  </div>
  <MainApp />


  <FooterApp />
</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import Card from './components/Card.vue';
import MainApp from './components/MainApp.vue';
import FooterApp from './components/FooterApp.vue';

import { contacts } from './components/data';

export default {
  name: 'App',
  components: {
    HeaderApp,
    Card,
    MainApp,
    FooterApp,

  },
  data() {

    return {
      lista: contacts
    }

  }


}
</script>

<style lang="css" scoped>
.height-black {

  padding-right: 300px;
  padding-left: 300px;
  background-color: black;
}
</style>