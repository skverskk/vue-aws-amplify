<template>
  <div id="app">
    <v-app-bar color="#970747" dark app fixed>
      <v-app-bar-nav-icon :to="{ name: 'Home'}"></v-app-bar-nav-icon>
      <v-toolbar-title>kenskversky.com</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only sansserif">
        <v-btn text :to="{ name: 'Register' }">REGISTER</v-btn>
        <v-btn text :to="{ name: 'Login' }">LOGIN</v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-content></v-content>
  </div>
</template>
<script>
// export default { name: 'Header' };
</script>
<style>
</style>
