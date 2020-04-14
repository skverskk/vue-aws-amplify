<template>
  <v-footer color="#970747" dark>
    <v-col class="text-center" cols="12">
      &copy; {{ new Date().getFullYear() }}
      <strong>ken.skversky.com</strong>
    </v-col>
  </v-footer>
</template>
<script>
export default { name: "Footer" };
</script>
<style>
.v-footer--absolute {
  width: auto !important;
}
</style>

