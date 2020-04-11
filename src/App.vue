<template>
  <v-app>
    <v-app-bar color="#fff">
      <NavHead />
    </v-app-bar>

    <HelloWorld />
    <v-footer>
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>
import NavHead from './components/NavHead';
import HelloWorld from './components/HelloWorld';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    NavHead,
    HelloWorld,
    Footer
  },

  data: () => ({
    //
  })
};
</script>
