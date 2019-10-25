<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Share</span>
        <span class="font-weight-light">Desk</span>
      </v-toolbar-title>
    </v-app-bar>

    <v-content>
      <Authentication/>
    </v-content>
  </v-app>
</template>

<script>
import Authentication from './components/Authentication.vue'

export default {
  name: 'App',
  components: {
    Authentication,
  },
  data: () => ({
    //
  }),
};
</script>
