<template>
  <HeaderApp />
  <MainApp />
  <MainApp v-for="contact in lista" :thumb="contact.thumb" :series="contact.series" :type="contact.type">

  </MainApp>

  <FooterApp />
</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import MainApp from './components/MainApp.vue';
import FooterApp from './components/FooterApp.vue';

import { contacts } from './components/data';

export default {
  name: 'App',
  components: {
    HeaderApp,
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

<style lang="scss" scoped></style>