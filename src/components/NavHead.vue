<template>
  <v-container class="mx-0">
    <v-toolbar color="#fff" flat>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <!-- <v-toolbar-side-icon></v-toolbar-side-icon> -->
      <v-toolbar-title class="titleHeader">kenskversky.com</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only sansserif">
        <v-btn text>REGISTER</v-btn>
        <v-btn text> LOGIN</v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </v-container>
</template>
<script>
export default { name: 'NavHead' };
</script>
<style>
.mainHeader {
  max-width: 1200px;
  font-weight: 300;
}
.titleHeader {
  font-weight: 600;
}
.sansserif {
  font-family: sans-serif, Arial, Helvetica;
  font-weight: 300;
}
</style>
