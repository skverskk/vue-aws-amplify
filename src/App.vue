<template>
  <v-app>
    <v-toolbar color="#970747" dark>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <!-- <v-toolbar-side-icon></v-toolbar-side-icon> -->
      <v-toolbar-title>kenkversky.com</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat>REGISTER</v-btn>
        <v-btn flat class="pr-8">LOGIN</v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <v-content>
      <HelloWorld />
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld
  },

  data: () => ({
    //
  })
};
</script>
