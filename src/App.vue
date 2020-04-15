<template>
  <v-app>
<<<<<<< HEAD
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
=======
    <Header />

    <v-content>
      <!-- <Main /> -->
      <router-view />
    </v-content>

    <Footer />
>>>>>>> 1aa037e... Fixed footer and Nav
  </v-app>
</template>

<script>
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
import HelloWorld from './components/HelloWorld';
=======
import Header from "./components/Header";
// import Main from "./components/Main";
import Footer from "./components/Footer";
>>>>>>> 1aa037e... Fixed footer and Nav
=======
import Header from './components/Header';
import Main from './components/Main';
import Footer from './components/Footer';
>>>>>>> parent of 1aa037e... Fixed footer and Nav
=======
import Header from "./components/Header";
// import Main from "./components/Main";
import Footer from "./components/Footer";
>>>>>>> 1aa037e... Fixed footer and Nav

export default {
  name: "App",

  components: {
<<<<<<< HEAD
    HelloWorld
=======
    Header,
    // Main,
    Footer
>>>>>>> 1aa037e... Fixed footer and Nav
  },

  data: () => ({
    //
  })
};
</script>
