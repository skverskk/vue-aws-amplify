<template>
  <v-footer color="#970747" max-width="1600" dark>
    <v-col class="text-center" cols="12">
      &copy; {{ new Date().getFullYear() }}
      <strong>ken.skversky.com</strong>
    </v-col>
  </v-footer>
</template>
<script>
export default { name: 'Footer' };
</script>
<style>
.mainFooter {
  max-width: 1200px;
  font-weight: 400;
}
.titleFooter {
  font-weight: 600;
}
.sansserif {
  font-family: sans-serif, Arial, Helvetica;
  font-weight: 400;
}
</style>
