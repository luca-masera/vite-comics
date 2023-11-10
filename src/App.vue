<template>
  <HeaderApp />
  <Header2App v-for="contact in lista" :thumb="contact.thumb" :series="contact.series" :type="contact.type">

  </Header2App>
  <MainApp />


  <FooterApp />
</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import Header2App from './components/Header2App.vue';
import MainApp from './components/MainApp.vue';
import FooterApp from './components/FooterApp.vue';

import { contacts } from './components/data';

export default {
  name: 'App',
  components: {
    HeaderApp,
    Header2App,
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