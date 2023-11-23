<template>
  <v-app>
    <v-main>
      <AppLayout />
    </v-main>
  </v-app>
</template>

<script>
import AppLayout from './components/AppLayout.vue';

export default {
  name: 'App',

  components: { AppLayout },

  data: () => ({
    //
  }),
};
</script>

<style>
@import url('https://fonts.cdnfonts.com/css/source-sans-pro');
html {
  overflow-y: visible !important;
  font-family: 'Source Sans Pro', sans-serif;
}
</style>
