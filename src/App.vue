<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
  
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
      >
        <span class="mr-2">Cerrar sesion</span>
        <v-icon>fas fa-address-book</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <v-container>
        <router-view/>
      </v-container>
    
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data: () => ({
    //
  }),
};
</script>
