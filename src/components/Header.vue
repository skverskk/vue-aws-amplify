<template>
  <v-container class="ma-0">
    <v-app-bar>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <!-- <v-toolbar-side-icon></v-toolbar-side-icon> -->
      <v-toolbar-title>kenskversky.com</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only">
        <v-btn text>REGISTER</v-btn>
        <v-btn text> LOGIN</v-btn>
      </v-toolbar-items>
    </v-app-bar>
  </v-container>
</template>
<script>
export default { name: 'Header' };
</script>
<style>
.mainHeader {
  max-width: 1200px;
  font-weight: 300;
}
</style>
